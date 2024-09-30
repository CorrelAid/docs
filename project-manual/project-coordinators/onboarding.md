# Onboarding

#### Goals

* enable the team to communicate with each other
* make data available to the team so that they can get started directly after the kickoff
* set up project tools


## Quick links

{% hint style="info" %}
The most important links from this section in one handy little box:

* [CorrelCloud folder](https://correlcloud.org/index.php/s/7PSskX9yN7RKmoi) with
  * confirmation of participation template
  * data security declaration template
  * example project folder with an example veracrypt container
* [Data privacy & security page](../data-security-and-privacy.md)
{% endhint %}

## Set up infrastructure and invite team members

### Set up Google docs/drive folder for team

1. Create folder for the team within [06\_projects](https://drive.google.com/drive/u/0/folders/0APzUn7ywXlbhUk9PVA)
2. In the folder, create a team\_base from the team\_base template (right-click -> Google docs --> from template -> template\_team\_base and rename / adapt it as necessary&#x20;
3. Share the folder (right-click on folder name -> share -> under general access set to "anonye with the link". Copy the link and pin it to the Slack channel as a bookmark.

### Copy and adapt declaration on data protection and security &#x20;

If the project has **any** data privacy requirements, the participants need to sign the [**declaration on data security**](../data-security-and-privacy.md#declaration-on-data-security).&#x20;

1. **copy** the German or English template from  [here](https://drive.google.com/drive/u/0/folders/1NR3bHoPWrzvR3pySiRQ61l\_BelMXksA\_) into the **project folder under 10\_project\_coordination**.
2. The declaration outlines the requirements for the highest security setup (including the requirement to create a separate user account), so please make sure to adapt them to your specific project by removing passages not needed for your project. If you're unsure, ask our data privacy team ([#data-protection-privacy Slack channel](https://correlaid.slack.com/archives/C04TN7Y01LP)).
3. Export as PDF and and reupload the PDF to the folder for the team (see previous step)
4. Team members should sign this declaration and send it to you (e.g. via Slack DM or email). You can then upload the signed declarations to the project folder in 10\_project\_coordination (see "Initial Slack communication with team members" below).

### Create Git repository

{% hint style="info" %}
**Who**: Project lead or project coordinator

**Requirements**: Membership in CorrelAid GitHub Repository.

Everyone who is a member of the CorrelAid GitHub organization can create repositories. You can check whether you are a member by going to ["Your organizations" in your GitHub profile](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-your-membership-in-organizations/accessing-an-organization). If you are not part of the organization, you can also ask another member of the organization or ask to become part of it by asking in #infrastructure Slack channel.
{% endhint %}

Usually, our project teams use GitHub for collaboration. To request a repository in the CorrelAid GitHub team, please proceed as followed:

1. in your project team channel, collect the GitHub of all team members.
2. On GitHub, click the new button
3. Pick one of the templates that we have created as boilerplates for project repositories. If none fits, create an empty repository with a README and (optionally) gitignore for the language(s) you'll be using. The existing templates are:

* [cookiecutter-python-analysis](https://github.com/correlAid/cookiecutter-python-analysis): template based on the popular cookiecutter project. suitable for analysis and machine learning projects.&#x20;
* [python-bare-template](https://github.com/correlAid/python-bare-template): minimal repository with Python gitignore
* [r-bare-template](https://github.com/correlAid/r-bare-template): minimal repository with R gitignore
* [r-project-template](https://github.com/correlAid/r-project-template): repository suitable for R analysis projects

4. Make sure to pick CorrelAid as the owner using the dropdown.
5. Choose repository visibility. Should be private by default unless it's an open source project and/or open data project
6. LICENSE can be left empty. If it's an open source project, choose MIT.&#x20;
7. In Settings -> General, enable Projects for the repository so that the team can create a kanban style board for their issues if they want to.&#x20;

Continue here once you have the GitHub profiles from the team members

7. invite team members **as outside collaborators** via Settings -> Collaborators and Teams. The default permission should be write, the team lead can also get manage.&#x20;

## Set up NextCloud for data transfer

{% hint style="warning" %}
This is necessary if the project data is sensitive or GDPR relevant. If you work with open data, you can probably skip this!
{% endhint %}

While our project teams usually use GitHub for their project work, we use our [NextCloud instance](../../wiki/infrastructure/nextcloud.md)  for the initial data transfer from the organization to CorrelAid and from CorrelAid to the project team members.&#x20;

Ask one of the project coordination admins (see below) to create a folder with your project id (e.g. 2021-02-COR) in the [**`06_projects`** folder](https://cloud.correlaid.org/apps/files/?dir=/06\_projects\&fileid=24332) structure to enable the data transfer. Project coordination admins with the necessary permissions are (so far):

* Pia (@Pia B / pia.b@correlaid.org)&#x20;
* Frie (@frie / frie.p@correlaid.org)

This folder will only be shared with you, the project team and the NPO representatives.

### Admin: How to create and share the folder

1. Go to the[ 06\_projects folder](https://cloud.correlaid.org/apps/files/?dir=/06\_projects\&fileid=24332)
2. Click the plus to create a new folder. Name it with the project id.&#x20;
3. Enter the folder by clicking on it. In it, create a folder`raw_data`&#x20;
4. Click on the share symbol next to the plus symbol. Invite everyone that needs access to the data via their email:

* other project coordinators with their CorrelAid email
* NPO representatives who share the data
* team members who need to access the data&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2023-07-13 at 5.02.06 PM.png" alt=""><figcaption><p>The share symbol is on the right end of the "breadcrumbs"</p></figcaption></figure>

{% hint style="danger" %}
Please make sure that you're only sharing the project folder and not the whole of 06\_projects! If you are **inside the project specific folder** (2000-00-TES in the example) it's fine!
{% endhint %}

## Initial Slack communication with team members

### Invite the team to the Slack channel

You should have [created a Slack channel](team-selection.md#create-slack-channel) for the project as part of the team selection phase. If you have not, you can do it now.&#x20;

Once you have your Slack channel, **invite or request to invite all selected team members** to the Slack channel as members by [inviting them to the Workspace and adding the created channel to the default Slack channels that they'll be added to](https://slack.com/help/articles/201330256-Invite-new-members-to-your-workspace#send-an-invitation-pre-ia) (we have a standard plan).&#x20;

If applicable, you should also **invite the representatives** of the NPO to the Slack workspace/channel. They might prefer to be invited as a guest if they also use Slack for their own organization. Check with them regarding their preferences. Having the NPO representative(s) on Slack makes team communication easier and increases NPO engagement.

### Welcome message

It's always nice if people join a Slack channel and there is already a message waiting for them to get a conversation going. Hence, you should post a welcome message.&#x20;

You can find a [template message here](https://docs.google.com/document/d/13CBLKgnwY60fQ8qDCgRYESbsn6sm5KB94eSEiOXUup4/edit#heading=h.qfda5e4lke3q).&#x20;

Goals of the message:

* get to know team members
* point out Google drive folder and other bookmarks on the Slack channel
* get necessary information and give actionable items
  * get GitHub profiles
  * sign declaration on data protection and security (if applicable)

## Coordinate date for kickoff workshop

Post an emoji poll on Slack to coordinate a date for the kickoff workshop.&#x20;

## Inform team members about data privacy & security

Make sure to inform your team members at some point about the data privacy and security considerations for the project. If you are unsure about what applies to your project, ask the project coordinator - they should know this. Express yourself as clearly as possible in DO's and DON'Ts. For examples, please see [here](scoping.md#data-privacy-and-data-access). You can do this as part of the kickoff or the onboarding process

If encryption is necessary for your project, share [this documentation page](../data-security-and-privacy.md#data-encryption) with them so that they can familiarize themselves with the options. A more detailed introduction to the tools - particularly VeraCrypt - should be part of the [kickoff](kickoff.md).

##



