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
3. Install the [**Docs to Markdown**](https://workspace.google.com/marketplace/app/docs\_to\_markdown/700168918607) **extension** and use it to export your google docs text to HTML directly (Extensions -> Docs to Markdown -> Convert, then HTML button). This will create raw HTML which you can copy into the code view in Directus. For larger texts, this is recommended.&#x20;

## FAQ

## What different Website links are there?

* live version: [https://correlaid.org](https://correlaid.org)
* preview version: [https://correlaid.pages.dev](https://correlaid.pages.dev)
* pull request previews for pull requests in the [GitHub Repository](https://github.com/CorrelAid/correlaid\_website/): those have the form https://\[random string].correlaid.pages.dev. You also need a CorrelAid email to access them via a code.

### The formatting of my blog post/content looks weird on the website

See [above](directus-content-management-system.md#draft-process-formatting) for tips how to manage formatting.&#x20;

