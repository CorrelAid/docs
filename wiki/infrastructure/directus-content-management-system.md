# Directus (Content Management System)

The CorrelAid Content Management System (CMS) is a tool built with Directus that serves content to the CorrelAid website. All the content on the CorrelAid website, including blog posts, events, and projects, originates from the CMS. This documentation provides an overview of how to use the CMS and explains the process of managing and publishing content on the website.

## **Accessing the CMS**

To access the CorrelAid CMS, visit [cms.correlaid.org](https://cms.correlaid.org) in your web browser.

If you need an account to contribute to correlaid.org, please reach out to the ["infrastructure-website-directus"](https://correlaid.slack.com/archives/C04DDHV6LUQ) channel on the CorrelAid Slack.

## **General Contribution Process**

To manage and publish content on the CorrelAid website, follow these general steps:

1. **Login:** Visit [cms.correlaid.org](https://cms.correlaid.org) and log in using your account credentials.
2. **Navigate to the desired collection:** Use the navigation menu sidebar on the left, select "Content" (the :package: icon) and then select the collection where you want to manage content, such as "Posts" or "Events."&#x20;
3. **Create a new entry:** Click on the "New Entry" button ( :heavy\_plus\_sign: icon) on the top right to create a new content entry within the selected collection. Fill in the required fields and provide relevant information.
4. **Publish an entry:** When you're ready to make an entry live on the website, ensure that the entry is set to **"published"**.
5. **Save and review changes:** After making edits or creating a new entry, remember to save your changes with the purlple :heavy\_check\_mark: button on the top right.
6. **Preview your changes:** Visit [correlaid.pages.dev](https://correlaid.pages.dev) and enter your correlaid.org email address. You will then be sent a link containing a code that you can use to access the preview website. If you don't have a correlaid.org email, [request a Google Workspace account](google-workspace.md#request-an-account).

## **Website Update Process**

The CorrelAid website (correlaid.org) is **automatically updated at 1 am,** using all content from Directus that is set to published. To ensure that your content appears on the website, follow these guidelines:

1. **Set entries to "published":** To include an entry on the website, set its status to "published".
2. **Check preview:** Before the automatic update, preview your entries to verify how they will look on the website. This step allows you to make any necessary adjustments before the website update occurs. If you are not happy yet with your content and need another day to work on it, set its status back to "draft".

Please note that the automatic update process may take some time, and the changes may not be immediately visible on the website.



## Tips and Tricks

### Draft process on Google Docs / other text editors and formatting <a href="#draft-process-formatting" id="draft-process-formatting"></a>

Most often, you might draft your content on google docs or other editors of your choice, e.g. to collaborate with others. This is a good process!

However, one problem is that Google docs and other editors (Word, VS Code) **assign their own formatting to text**. This means when you copy your text to the text editor within Directus, it might still carry this additional formatting with it. There are three things you can do for it:

1. **Clear formatting button**: highlight all the text you copied in and click the clear formatting button (looks like the italic button "_I_" but with a little x). This will remove styles from the text.

Sometimes this is not sufficient, e.g. for bullet point lists, Google docs creates an extra `<p>` tags for each bullet point causing the spacing between bullet points to be quite large. You can see this in the code view of the editor (accessible via the `<>` button). In this case:

2. **Remove extra tags manually** in the code view. This works well for smaller texts.
3. Install the [**Docs to Markdown**](https://workspace.google.com/marketplace/app/docs\_to\_markdown/700168918607) **extension** and use it to export your google docs text to HTML directly (Extensions -> Docs to Markdown -> Convert, then HTML button). This will create raw HTML which you can copy into the code view in Directus. For larger texts, this is recommended.

### Add a Video to WYSIWYG

1. Log in at vimeo.com
2. Open the video you want to embed
3. Copy the html code you see when you click on "Embed" and on "Fixed", but remove the height and width attributes and add the "dnt=1" url parameter (do not track). This is an example for what the resulting html code should look like:

```html
<iframe src="https://player.vimeo.com/video/827419927?h=7cc5391f99&amp;dnt=1" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>
```

4. In the WYSIWYS field in directus, click on "Edit Source Code" (the <> icon) and paste the html code at the place where you want the video to appear. The video wont be displayed when you switch back to the normal edit view, but it should be displayed on the website.

### Removing empty translations

Some content allows for translations, but recognizes that not all languages (currently English and German) might be provided. In such cases the website has logic build into it that will use the language with existing content independent of what the user has currently selected. For instance the German version of the website will show blog posts that are only available in English. Currently this behavior is used for blog posts and jobs.

In Directus, it can unfortunately happen that a translation ends up existing without any content. So the system for instance thinks there is a German version of a blog post but its actually empty. This can, for instance, happen when content is added to a particular language/translation by accident and is removed again afterwards. Ideally these empty unneeded translations are then removed manually. Since this is not straight forward the concrete steps follow. As an example we consider posts but it works similarly in other collections.

1. Identify the `ID` of the blog post with the empty translation. This should be in the posts collection table. If its not there it can be added as a column with the `+` sign in the upper right corner.
2. Right click in the menu on the left, that is listing the collections. From the context menu choose "Show Hidden Collections". Make sure you right click in the menu, but not on a particular collection. Otherwise a different context menu containing "Edit Collection" will show up.
3. Choose the collection "Posts Translations"
4. Find the Translation that has as `Posts ID` the ID identified in step 1.
5. Select that row and hit the delete button in the top right.
6. Right click in the menu on the left to "Hide Hidden Collections"  again.

## FAQ

## What different Website links are there?

* live version: [https://correlaid.org](https://correlaid.org)
* preview version: [https://correlaid.pages.dev](https://correlaid.pages.dev)
* pull request previews for pull requests in the [GitHub Repository](https://github.com/CorrelAid/correlaid\_website/): those have the form https://\[random string].correlaid.pages.dev. You also need a CorrelAid email to access them via a code.

### The formatting of my blog post/content looks weird on the website

See [above](directus-content-management-system.md#draft-process-formatting) for tips how to manage formatting.&#x20;

## Admin

### Directus Deployment

Directus is set up with Terraform and Ansible. Find the repo [here](https://github.com/CorrelAid/CorrelIaC). It runs on Azure on a VPS connected to a managed Postgres Database. The terraform currently only exists locally, but we plan to migrate this to the cloud in the future.

### Frequent Bug Fixes

#### ID not unique

It has happened multiple times that suddenly, when someone wanted to create a new entry in a collection, they were shown the error message "ID not unique". This seems to be a bug with Directus. The cause is that the automatic increment of ids in the corresponding Postgres table was somehow reset, so that entries are being created with ids that already exist. Fix this in the following way:

1. Connect to the server Directus is running on (the ip of this server is the only one that can connect to the database). Ask on Slack for your ssh key to be added to the server.
2.  Use psql to connect to the Database like this:\


    {% code overflow="wrap" fullWidth="true" %}
    ```bash
    psql "host=hostname port=5432 dbname=main user=user password=password sslmode=require"
    ```
    {% endcode %}

    \
    Find the credentials on bitwarden.
3. Identify the collection causing the error. Sometimes it is not the collection you tried to create an entry in, but some other collection related to it, for example translations.
4.  Execute the following SQL code (insert the name of the collection):\


    {% code overflow="wrap" fullWidth="true" %}
    ```sql
    SELECT SETVAL('public."<Collection>_id_seq"', (SELECT max(id) FROM public."<Collection>")); 
    ALTER TABLE public."<Collection>" ALTER COLUMN id SET DEFAULT nextval('"<Collection>_id_seq"'::regclass);
    ```
    {% endcode %}

