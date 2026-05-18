# Directus (Content Management System)

## CorrelAid CMS Documentation

The CorrelAid Content Management System (CMS) is a tool built with Directus that serves content to the CorrelAid website. All the content on the CorrelAid website, including blog posts, events, and projects, originates from the CMS. This documentation provides an overview of how to use the CMS and explains the process of managing and publishing content on the website.

### Accessing the CMS

To access the CorrelAid CMS, visit [cms.correlaid.org](https://cms.correlaid.org) in your web browser.

If you need an account to contribute to correlaid.org, please reach out to the `infrastructure-website-directus` channel on the CorrelAid Slack.

### Important Info

**Do not upload sensitive files to Directus!**

### General Contribution Process

To manage and publish content on the CorrelAid website, follow these general steps:

1. **Login**: Visit [cms.correlaid.org](https://cms.correlaid.org) and log in using your account credentials.
2. **Navigate to the desired collection**: Use the navigation menu sidebar on the left, select "Content" and then select the collection where you want to manage content, such as "Posts" or "Events."
3. **Create a new entry**: Click on the "New Entry" button on the top right to create a new content entry within the selected collection. Fill in the required fields and provide relevant information.
4. **Publish an entry**: When you're ready to make an entry live on the website, ensure that the entry is set to `published` if this field exists.
5. **Save and review changes**: After making edits or creating a new entry, remember to save your changes with the purple save button on the top right.
6. **Preview your changes**: See the Previewing changes section below.

The CorrelAid website ([correlaid.org](https://correlaid.org)) is automatically updated at 1 am, using all content from Directus that is set to `published` (if this field exists).

### Previewing changes

The preview site is available at [preview.correlaid.org](https://preview.correlaid.org) and is protected by HTTP Basic Auth. Credentials are stored in Bitwarden.

A few things to know about the preview environment:

* It fetches content **live** from Directus on a 15-second interval, so any change you save in the CMS shows up on the preview site within \~15 seconds without a rebuild. Entries with status `preview` are included in addition to `published` ones.
* It runs in **dev mode**, which makes the site noticeably slower than production — the server is small and pages are rendered on demand. This is expected.
* Because content is fetched live, you can also preview edits to pages authored in MDX (see below) directly from [cms.correlaid.org/admin/content/pages](https://cms.correlaid.org/admin/content/pages).

### Editing MDX content

Pages are stored as [mdx](https://mdxjs.com/) Markdown with embedded JSX components. There is a learning curve compared to a WYSIWYG editor, but you see everything at a glance and it is easier for developers to work with.

To make MDX easier to author inside Directus, we use a CorrelAid-developed extension: [`directus-extension-mdx-editor`](https://github.com/CorrelAid/directus-extension-mdx-editor). The editor replaces the plain textarea on MDX fields with a CodeMirror-based editor and gives you syntax highlighting, autocomplete and other things.

If you see an orange squiggle under a component name, it usually means you mistyped the component or that the component does not exist — check the autocomplete suggestions. If you see a red squiggle, the MDX won't render at all on the website; fix the syntax before saving.

### Removing empty translations

Some content allows for translations, but recognizes that not all languages (currently English and German) might be provided. In such cases the website has logic built into it that will use the language with existing content independent of what the user has currently selected. For instance, the German version of the website will show blog posts that are only available in English. This behavior is currently used for blog posts and jobs.

In Directus, it can unfortunately happen that a translation ends up existing without any content — so the system thinks there is, for example, a German version of a blog post, but it is actually empty. This can happen when content is added to a particular language/translation by accident and removed again afterwards. Ideally these empty translations are removed manually. The steps below use posts as an example, but it works similarly in other collections.

1. Identify the ID of the blog post with the empty translation. This should be in the Posts collection table. If it is not visible there, it can be added as a column with the `+` sign in the upper right corner.
2. Right-click in the menu on the left that lists the collections. From the context menu choose **Show Hidden Collections**. Make sure you right-click in the menu but not on a particular collection — otherwise a different context menu (containing "Edit Collection") will show up.
3. Choose the collection **Posts Translations**.
4. Find the translation that has as `Posts ID` the ID identified in step 1.
5. Select that row and hit the delete button in the top right.
6. Right-click in the menu on the left and choose **Hide Hidden Collections** again.

### FAQ

#### What different website links are there?

* **Live version**: [https://correlaid.org](https://correlaid.org)
* **Preview version**: [https://preview.correlaid.org](https://preview.correlaid.org) (HTTP Basic Auth; credentials in Bitwarden). Fetches Directus content live and runs in dev mode, so it is slower than production.
* **Pull request previews** for pull requests in the GitHub repository: those have the form `https://[random string].preview.correlaid.org`.&#x20;

#### My MDX content doesn't render correctly on the website

Check the editor for red or orange squiggles — those indicate MDX syntax errors or unknown components. Open the page on [preview.correlaid.org](https://preview.correlaid.org) to see the rendered result without waiting for the next nightly build.

