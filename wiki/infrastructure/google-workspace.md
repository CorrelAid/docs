# Google Workspace

{% hint style="warning" %}
Work in progress. Will be added to over the course of June/July 2022 as we roll out Google Workspace.
{% endhint %}

## Migration

As questions / information regarding the migration to Google Workspace are only temporarily useful, they can be found in [this pad](https://pad.correlaid.org/s/B11wgILu9).

## Get started&#x20;

1. Set up [2-factor authentification](https://myaccount.google.com/u/2/signinoptions/two-step-verification/enroll-welcome?hl=en) if it is a personal account (not recommended for group accounts because of log-in problems)
2. check out which [Google Groups](https://groups.google.com) you're in. This determines which [Google Drive Shared Drives](https://drive.google.com/drive/u/2/shared-drives) / folders you have access to.
3. Read the [Google Drive "Get started".](google-workspace.md#get-started-1)
4. Read the Google Mail "Get started".



## Google Groups

### What is a Google Group?

> Groups such as project teams, departments, or classmates can communicate and collaborate using Google Groups. If you want to invite a group to an event, or share documents with a group, you can send a single email to everyone in the group. ([Source](https://support.google.com/a/users/answer/9304805?hl=en))

#### How do we use Google groups?

We use Google groups to arrange our volunteers into different groups, according to their interest and level of involvement and responsibility in CorrelAid. For example, each local chapter has two groups:

* `lc-konstanz`: all people involved in the local chapter. They get access to the CorrelAidX shared drive where they can work on documents.&#x20;
* `lc-konstanz-heads`: the heads of the local chapter. They can manage members of the `lc-konstanz` group, and get access to the konstanz@correlaid.org email address/account.&#x20;

#### Which groups am I in?&#x20;

You can see your group membership(s) at [https://groups.google.com/my-groups](https://groups.google.com/my-groups). Each group has a description which describes what members of this group can do/what they get access to.

#### Where can I see all groups?

You can find an overview of all groups at [https://groups.google.com/all-groups](https://groups.google.com/all-groups). Each group has a description which describes what members of this group can do/what they get access to.

### User Management/Admin

If you are manager of a Google Group, you can add/remove members by going to [https://groups.google.com/my-groups](https://groups.google.com/my-groups) and then clicking on the group you want to manage. In the sidebar on the left hand side, you'll find "People". There you can add/remove members.

## Google Drive

{% hint style="info" %}
Tip: Download [Drive for Desktop](https://www.google.com/drive/download/) (MacOS / Windows) to also access your files via your file explorer.&#x20;
{% endhint %}

### Get started

1. Go to [https://drive.google.com](https://drive.google.com) and make sure you are logged into your CorrelAid Google Workspace account.
2. This will redirect you to your "My Drive". There are three ways to interact with Google Drive which are accessible via the sidebar on the left:
   1. :warning:My Drive: your personal Drive. It shows the most recent documents you worked on and gives you the option to create new files. Do not create files here unless they are really just for you - they will not be shared with anyone by default.&#x20;
   2. :white\_check\_mark: Shared Drive: The shared drive system where people have access to files relevant to them. If you create/edit/delete files here, your teammates can directly access them as well. The shared drive system replaces NextCloud (with **exceptions for sensitive project data**, see below).&#x20;
   3. :white\_check\_mark: Priority: a new way of creating your own personal "view" of what is in Shared Drives. You can "pin" documents and sort them into workspaces - which won't affect the way things are organized in Shared Drive. You can use this freely as you like. Just remember: this is just for you. You can make Priority your default Drive landing page by changing it in the settings (:gear: in the top right).
3. Go to Shared Drives and explore. You should have access to the [`00_assets` drive](https://drive.google.com/drive/u/0/folders/0AFVtSXmGUxMCUk9PVA) where you can find template slides, the CorrelAid logo and other useful templates and documents.&#x20;
4. If you have CorrelAid files/content somewhere else/on your personal laptop: Read the "What (not) to store on Google Drive" subsection below. Then, migrate any files you have on your personal laptop / your personal Google account. For the latter,[ see the FAQ](../faq.md#how-do-i-migrate-google-docs-sheet-slides-from-my-personal-account).&#x20;
5. Setting up a local chapter? There is a suggestion for how to structure your local chapter folder in the `99_example_chapter`. Copy-paste that to your own chapter folder to get going!
6. Check out [this article](https://support.google.com/a/users/answer/9310349?hl=en) to learn more about how you can optimize your personal drive setup / find things faster! :)&#x20;

### What (not) to store on Google Drive&#x20;

****:x:**You must not:**

* store project data from NPO partners if it is [GDPR relevant](../../project-manual/data-security-and-privacy.md#personal-data-gdpr)
* store any other project data from NPO partners
* don't store/write down [special characteristics](https://gdpr-info.eu/art-9-gdpr/) (ethnicity, religion, political beliefs...) of other people (also incl. Google Docs/Google Sheets) -> for those cases, please use NextCloud or a [private CodiMD](codimd.md#setting-permissions).

:warning:**Under certain circumstances**

* for meetings/information concerning/including external partners: ask them beforehand whether it is OK if you use Google Docs to write meeting minutes/plan things including them. Some organizations/partners might not want information about them on US servers. Respect that and use [NextCloud](correlcloud.md) or a [CodiMD](codimd.md) instead.&#x20;
* avoid storing personal data from CorrelAiders on Google Drive. Names and CorrelAid email addresses should be ok, but for instance, if you need to collect postal addresses, use a [Kobo form ](kobo.md)instead of Google Forms.
* you can use Google Drive to transfer/store [non-GDPR relevant](../../project-manual/data-security-and-privacy.md#types-of-data) data from the partner organization under the condition that the project partner **consented to this in written form.**

:white\_check\_mark: You can keep on the Google Drive:

* meeting minutes for internal purposes, e.g. discussing the planning of an internal event&#x20;
* additional material such as certificates of attendance or data privacy agreements
* use Google Drive to transfer/store Open Data

### Guidelines & Best Practices

#### Avoid link sharing when possible

* :white\_check\_mark: Copy the link from the browser line and share with your team. They should be able to open the document because they have access to the Shared Drive folder where you put the file.&#x20;
* :x:Avoid sharing the document via the "Share" button, especially changing permissions from Restricted to something more permissive. If you find yourself repeatedly sharing files via the Share functionality with the same people, consider requesting Google Workspace accounts for them instead.
* :warning:Of course, sometimes it makes sense to share documents via the "Share" functionality, e.g. with an outside partner (partner organization, guest speaker, ...). In that case, you have to:
  * Click the "Share" button
  * Click on "Get Link"
  * Change "Restricted" to "Anyone with the link" (for outside people) or "CorrelAid e.V." (e.g. for internal memos)

#### Use Shared Drives instead of My Drive

Files in MyDrive are not shared in the Shared Drive system, so other people won't be able to access them. This hinders collaboration. Hence, make sure to always create new documents from a Shared Drive location/folder.&#x20;

### Template slides & documents

We have added templates and will add more in the future, e.g. the [Slide Master](https://docs.google.com/presentation/d/14oTzIhF78U64SHaRu704SaS2tCVyaFS-dUWD52OrW0w/).

How to use a template:

#### The "proper way"

> Choose an option:
>
> * From the [Docs](https://docs.google.com), [Sheets](https://sheets.google.com), [Slides](https://slides.google.com), [Forms](https://forms.google.com), or [Sites](https://sites.google.com) home screen, at the top, select one of the featured templates. Click **Template gallery** to see additional templates.\
>   **Note:** If you can't find **Template gallery**, go to [Display or hide Template gallery](https://support.google.com/a/users/answer/9308885#displayorhide).
> * If you already have a file open in one of the Docs editors, click **File**![and then](https://storage.googleapis.com/support-kms-prod/Th2Tx0uwPMOhsMPn7nRXMUo3vs6J0pto2DTn)**New**![and then](https://storage.googleapis.com/support-kms-prod/Th2Tx0uwPMOhsMPn7nRXMUo3vs6J0pto2DTn)**From template** and select the template you want.
> * From [Drive](https://drive.google.com), click **New** and next to **Google Docs**, **Sheets**, **Slides**, **Forms**, or **Sites** point to the Right arrow ![""](https://storage.googleapis.com/support-kms-prod/Y3Ktnkg25mjbIYw5YRXiBevtMUCeHh8xM5uz) and click **From a template**.

Source: [https://support.google.com/a/users/answer/9308885?hl=en](https://support.google.com/a/users/answer/9308885?hl=en)&#x20;

#### Make a copy

Go to the template, click on "File" and then "make a copy". Make sure to store in the Shared Drive.&#x20;

### Migration

See the [Migration pad](https://pad.correlaid.org/s/B11wgILu9#file-migration-1) for questions & answers related to the Migration from Nextcloud / personal Google docs to Google Drive.

#### How do I migrate Google Docs/Sheet/Slides from my personal account?&#x20;

{% hint style="warning" %}
Only transfer CorrelAid-related files to the Google Workspace.&#x20;
{% endhint %}



1. Go to MyDrive of your personal [Google Drive](https://drive.google.com)&#x20;
2. Select the files you want to transfer to your CorrelAid Workspace account (you can select multiple files by holding Cmd respectively CTRL).
3. Right-click and download. This will download a zip file. Unzip it.
4. Delete the files from your personal Google account (right click > Move to bin) to avoid confusion with multiple files floating around.&#x20;
5. Switch to your CorrelAid account on [Google Drive](https://drive.google.com). Click  :gear: on the top right, open the Settings and make sure the "Convert Uploads" tickbox is set. This ensures that the downloaded files are automatically converted to Google Docs/Slides/Sheets.
6. Go to the Shared Drive location where you want to dump your files. Right-click > folder upload. Select your unzipped folder in your Downloads folder.&#x20;
7. After the upload has completed, move the files by right-clicking > "Move to". Alternatively, download [Drive for Desktop](https://www.google.com/drive/download/) to move files more quickly using your file explorer.
8. Update links to files, e.g. pinned in Slack channels.

#### How do I migrate a CodiMD pad?

{% hint style="info" %}
did you know you can also use Markdown in Google Docs now? You can enable Markdown support by going to Tools -> Preferences -> Tick "Automatically detect markdown"
{% endhint %}

1. In your CodiMD, click on the "eye" to only show the formatted text.
2. Use CMD (mac) / Ctrl + A to select all the text
3. Copy (ctrl/cmd + c)
4. Create new Google Doc
5. Paste (ctrl/cmd + v)
6. Delete the Pad from CodiMD via the [permission dropdown ](codimd.md#setting-permissions)

### FAQ

See[ Google Drive FAQ](../faq.md#google-drive) in the overall FAQ.

## Google Forms

### Events / Signup and Feedback forms

Due to GDPR concerns, please avoid using Google Forms for anything requiring a sign up/personal data. Instead use:

* Pretix for events -> Frie or Phil can give you access
* [KoboToolbox](kobo.md) for forms such as feedback surveys or signup for internal events (e.g. a summer party) -> Frie or Phil can give you access

## Google Mail

coming soon.

## Google Calendar

### Personal calendar

{% hint style="info" %}
start using after email migration
{% endhint %}

You have your personal CorrelAid calendar(s) which you can find at [calendar.google.com](https://calendar.google.com).&#x20;

{% hint style="success" %}
You can also subscribe to your personal calendars from other accounts (e.g. Outlook, Google, Posteo) so that you already have your other appointments in view when planning your CorrelAid volunteering. A quick Google search should help you out:)
{% endhint %}

#### Visibility of your calendar / sharing of your personal calendar

By default, your personal CorrelAid calendar can be seen by other CorrelAiders as well - **they can't see the details of the event(s), just when you're busy**.  You can change this setting in the sharing & permissions settings of your calendar(s). See [this page](https://support.google.com/calendar/answer/37082) for the how-to and other things you can do (e.g share with specific person or group)

#### Arrange a meeting

You can arrange a meeting with someone else by using the "Meet with" box.

#### Displaying  calendars from others

Example use case:

* you want to see the calendar of one of the CorrelAid employees to send them a meeting invite\*

You can find and display calendars of individual people by clicking the plus next to “Other calendars”, then “subscribe to new calendar” and then typing the name of the person

\*don’t just send people meeting invites out of the blue - that’s rude. Always ask first, e.g. via Slack DM :)

### Group calendar

#### Create shared / group calendars

Example use cases:

* CorrelAidX chapter calendar
* global CorrelAid event calendar
* Calendar for Mentoring Program

You can create a group calendar and share it with individuals or group(s) within the workspace as described [here](https://support.google.com/a/answer/1626902?hl=en). You can find the list of all groups [here](https://groups.google.com/all-groups). You can give different groups different permissions, e.g. the `lc-heads` group editing rights and the `lc` group reading rights.

You can also [share the calendar with the public](https://support.google.com/calendar/answer/37083).

#### Displaying group calendars

Example use case:

* you want to display a group calendar, e.g. the calendar of your local chapter

Ask one of the group admins (e.g. the local chapter head) to send you the calendar ID, as described [here](https://support.google.com/a/answer/1626902?hl=en).

## Google Meet&#x20;

See page on [Video conferences](zoom.md#google-meet).
