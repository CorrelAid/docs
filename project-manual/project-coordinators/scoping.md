# Scoping

Quick links

{% hint style="info" %}
The most important links from this section in one handy little box:

* [Scoping Phase Google Docs Template](https://docs.google.com/document/d/10m0qPGRNbGi0LYyMc6LYTxner5WSMYtUAIHkIHZwHTg/edit)
* [Data Maturity Framework](http://www.datasciencepublicpolicy.org/home/resources/datamaturity/)
* [Call for Applications Google Docs Templates (🇬🇧 🇩🇪)](https://drive.google.com/drive/u/0/folders/1KR7dxTdLRhtDEsQspLnEEtA2vsYM7gan)
* ["When do we do a project?" - Guide](../project-decision-guide.md)
* [GitHub Projects repository](https://github.com/CorrelAid/projects) with Kanban board
{% endhint %}

## Scoping

{% hint style="info" %}
**Relevant CorrelAid actors**

* project coordinator
* project lead (if found early)
{% endhint %}

#### **Goals**

1. decide **whether** we should do a project with the organization
2. if yes, scope the project

#### **Checklist**

{% hint style="success" %}
* [ ] add project to Kanban board
* [ ] talk to NPO
* [ ] decide to do project with NPO
* [ ] scope the project
* [ ] get information on data security / privacy & data access
* [ ] fix date of the [kickoff workshop](kickoff.md#location) if possible (especially when in-person)
* [ ] if possible, find a prospective team lead and involve them early into the process
* [ ] confirm team members
* [ ] confirm team lead (if you had to "promote" a team member)
{% endhint %}

### Add project to Kanban Board

We have a Kanban board in GitHub to track the progress of all projects. Once you enter into more the scoping phase with a non-profit organisation, make sure to add it to the kanban board. This way, we have a global overview over all projects and you can also check out other projects and learn from their progress.

How to add your project to the Kanban board? Learn more on this page:

{% content-ref url="github-projects-repository.md" %}
[github-projects-repository.md](github-projects-repository.md)
{% endcontent-ref %}

### Communication Mode

In the scoping phase, you should aim to communicate regularly and repeatedly with the NPO to make sure that we a) really want to do a project with them and b) can define a project which will work for both the NPO and the CorrelAid team. Usually, **2-4 iterations over 1-4 weeks** are necessary to define a project so that we can send it out via our newsletter.

In principle, you are free in how you communicate with the NPO: email, phone, video call or in-person are all valid choices. However, aim for **at least one personal conversation** (i.e. not email). Ideally, you have a mix of personal formats with follow-up emails with a short protocol summarizing what you discussed on the phone, in the video call or in-person. This way you can make sure that you and the organization had the same take-aways from the call and that you have a written, agreed-upon record to come back to.

You can take notes on [Google Workspace](../../wiki/infrastructure/google-workspace.md) or on our CodiMD instance [pad.correlaid.org](broken-reference). You can copy the [scoping template](https://docs.google.com/document/d/10m0qPGRNbGi0LYyMc6LYTxner5WSMYtUAIHkIHZwHTg/edit) which includes a rough structure and some helpful questions (see below). Please store your notes in either the **CorrelAid** Google Workspace or the CodiMD instance so that other team members have access to that. Avoid storing content on your personal Google Drive.&#x20;

There are several things you need to discuss with the NPO over the course of the scoping phase:

1. content and scope of the project
2. expectation management & organization commitments
3. data security / privacy & data access
4. timeline
5. team size & composition

### Content and scope of the project

This is arguably the most interesting part. Here, you and the NPO should elaborate together what should be part of the project and how CorrelAid volunteers can help the NPO while at the same time having a good learning experience.

**What's a good CorrelAid project? When should we do a project? When not?**

Please refer to the guide to find out whether we should do a project in the first place.

{% content-ref url="../project-decision-guide.md" %}
[project-decision-guide.md](../project-decision-guide.md)
{% endcontent-ref %}

{% hint style="warning" %}
Finding all this out might require a call with the potential partner, so don't make promises too early before you have established that this will be a good idea.
{% endhint %}

Hence, it is important to get as good a picture of the situation as possible. While this process is not standardized, here are some resources:

* a catalogue of possibly helpful questions can be found in the [scoping phase template](https://docs.google.com/document/d/10m0qPGRNbGi0LYyMc6LYTxner5WSMYtUAIHkIHZwHTg/edit).
* you can also draw from the data maturity framework from the [_Center of Data Science & Public Policy_](http://www.datasciencepublicpolicy.org/home/resources/datamaturity/). It has a "Data and Tech Readiness Scorecard" and a "Organizational Readiness Scorecard". They can be downloaded [here](http://www.datasciencepublicpolicy.org/wp-content/uploads/2018/05/Data\_Maturity\_Framework\_4.28.16.pdf).
* we have adapted both scorecards into German. They can be downloaded [here](https://correlaid.org/material/datenreifegradmodell.pdf) and [here](https://correlaid.org/material/organisationsreifegradmodell.pdf).

{% hint style="warning" %}
While coming to an agreement on the content and scope of the project is important, you should leave enough room so that goals can be adjusted later on in the project if necessary. Avoid going into too much technical detail in the project description. Focus on **what** the organization needs and fix the rough technologies (Python or R? Data Visualization or Machine Learning Model?), and leave the more detailed **how** to the project team.
{% endhint %}

### Expectation management & Organization commitments

Another important part of the ideation phase is expectation management. You should make clear that:

* ... CorrelAid is a **volunteer-based organization**. That means that the project team members are volunteers who will usually spend 3-5 hours per week on the project. It also means that rarely volunteers might drop out of the project because they're suddenly faced with other, unforeseen challenges in their life.
* ... CorrelAid projects **do not only serve the NPO but also our volunteers** by providing learning opportunites (see info box above). This also means that our project teams are diverse such that we do reserve at least one spot for a less experienced data scientist.

Fortunately, almost all NPOs will totally understand those points because they also rely on volunteering in their work. :)

In addition to those "soft" expectation management issues, you should also get the OK from the organization that they are willing and able to:

* support the project team over the course of the project, i.e. they will be available for regular calls / email communication / meetings to answer questions and give feedback
* provide a room for the [kickoff](kickoff.md) and pay for travel and accomodation for project team members. Those costs usually amount to \~500-1000 euro. If the kick-off workshop is virtual, they are willing to participate online.

### Data privacy & data access

Data protection and privacy is very important to CorrelAid. Hence, you should find out early what kind of data is to be collected and/or analysed in the project so that the project lead and project team can take on appropriate measures to correctly store and process the data.

To make yourself familiar with the different types of data - especially the concept of "personal data" -, please check out the "[types of data](../data-security-and-privacy.md#types-of-data)" section of the data security & privacy page:

{% content-ref url="../data-security-and-privacy.md" %}
[data-security-and-privacy.md](../data-security-and-privacy.md)
{% endcontent-ref %}

After you've familiarized yourself with the definitions, you should be able to decide on the right project setup together with the NPO by asking the following questions.

**Will any kind of personal data be involved in the project?**

**If** 👍:

Most of the times, CorrelAid teams will get a pseudonymized version of the data (i.e. individuals are still identifiable with the use of additional information). But even if the partner organization claims the data is truly anonymized, CorrelAid teams should not rely on that claim. Hence, in any case CorrelAid teams dealing with any kind of personal data should always adhere to the following setup:

{% hint style="info" %}
**Project setup**

* DO: encrypt the data on local machines (see [howto](../data-security-and-privacy.md#data-encryption))
* DO NOT: upload data to GitHub / GitLab (see howto)
* DO: team members and NPO need to sign the _obligation to observe data secrecy_ _\*\*_(de: Datenschutzverpflichtungserklärung) (download it here)
* DO (if very sensitive data): team members create separate user account on their machine just for the project
{% endhint %}

**If** 👎:

If the project does not involve personal data, it depends on the requirements and wishes of the NPO which data protection & security measures the project team needs to adopt. Here are the questions to ask the NPO.

#### **Does the data have to be encrypted locally?**

Make sure the organization understands the attack vector, i.e. if a laptop of a team member was stolen, the data could be extracted from the hard drive.

If data can be stored unencrypted, CorrelAid team members do not need to ensure encryption which can be easier, especially for team trainees.

**Can the data be uploaded to a private GitHub / GitLab repository?**

Make sure that the organization understands that GitHub and GitLab are both companies which most likely have their servers in the US. CorrelAid does not self-host a version control service.

With a private repository access to the repository would be limited to team members and the project coordinator. In consequence the data would only be accessible to team members and the project coordinator.

If data can be stored on GitHub / GitLab, they can be put under version control, i.e. changes to raw data can be tracked and reverted easily if necessary. In addition, it makes collaboration in the team easier because the setup is shared through GitHub / GitLab.

**Can the code and data be published to a public GitHub / GitLab repository?**

If the organization decides to open source the code and data to the public, it is accessible to everyone.

Other organizations and data scientists can make use of our work and we would contribute to open source.

If the NPO decides that they are ok with open sourcing code + data, you should help them choose a license for data and code. [https://choosealicense.com/](https://choosealicense.com/) is a good resource for deciding this.

| Question                                                                   | Answer | Consequence                                                                                                                                                                                                                                                                                                 |
| -------------------------------------------------------------------------- | ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Can the data be stored unencryped on the local machines?                   | ✅      | Team members _**do not need**_ \_\*\*\_to use VeraCrypt or encrypt their home folder.                                                                                                                                                                                                                       |
| Can the data be stored unencrypted on the local machines?                  | ❌      | Team members _**need**_ to use VeraCrypt or encrypt their home folder.                                                                                                                                                                                                                                      |
| Can the data be uploaded to a private GitHub / GitLab repository?          | ✅      | Team members _**can**_ _**upload**_ raw and all kinds of processed data to GitHub / GitLab. The initial data transfer to the project team can be done using GitHub / GitLab.                                                                                                                                |
| Can the data be uploaded to a private GitHub / GitLab repository?          | ❌      | Team members _**cannot**_ _**upload**_ raw and processed data to GitHub / GitLab. Instead, they should document relevant folder structures in the README of the repository and put the data folder in .gitignore. The initial data transfer to the project team _**needs**_ to be done via the CorrelCloud. |
| Can the code and data be published to a public GitHub / GitLab repository? | ✅      | The repository _**can be public**_. Appropriate licences for code and data _**need**_ to be chosen.                                                                                                                                                                                                         |
| Can the code and data be published to a public GitHub / GitLab repository? | ❌      | The repository _**cannot be public.**_                                                                                                                                                                                                                                                                      |

{% hint style="warning" %}
**Get written confirmation from NPO**

Always confirm what you discussed in in-person or in calls via a **clearly formulated email** with the NPO, e.g. by copying the table above with the answers of the NPO and asking for their written confirmation of the agreed privacy rules. You can store the email in the Google Drive folder where you keep the organisational details of the project.
{% endhint %}

### Timeline

Finally, you should also agree on a rough **timeline**. A usual project can look like:

| Phase                                | Approximate Duration                                                       |
| ------------------------------------ | -------------------------------------------------------------------------- |
| _Send out call for applications_     |                                                                            |
| Collecting applications              | 1.5-2 weeks                                                                |
| Team selection                       | 1 week                                                                     |
| Onboarding + coordination of kickoff | 1-5 weeks                                                                  |
| _Kickoff workshop_                   | _either online (1-3 hours or projectcycle kickoff) or a in-person weekend_ |
| Project work                         | 1-6 months                                                                 |
| _Handover workshop_                  | _either online (1-3 hours) or a in-person meeting (1-3 hours)_             |
| Follow-up                            | immediately after handover workshop and after several months               |

Please always add in a bit of buffer. Holidays etc. are a thing, so you shouldn't plan with all volunteers working 3-5 hours on the project all weeks.

{% hint style="info" %}
**Deadlines can be helpful!**

If the organization has a certain **deadline** (e.g. the launch of a new website, their annual members meeting), use it to mark the end of the project. This way, the project team has a clear goal to work towards!
{% endhint %}

### Team

A project needs a **team**. Before you send out the call for applications, you should define roughly how you would like the team to look like.

#### Size

Usually, CorrelAid teams consist of 4-6 people, but there can also be smaller teams (e.g. a two-person team) or larger teams if the project is very comprehensive and there are several sub-projects that can be worked on simultaneously.

{% hint style="warning" %}
**Team size - always overstaff!**

Previous experience has shown that there is usually a "loss" of 1-2 people over the course of a project. Hence, if in doubt whether you want `x` or `x+1` people on the team, rather go with `x+1`. **Rather overstaff than understaff!**
{% endhint %}

#### Roles

With regards to skills, it can be useful to think of different "roles" that you want to fill. In a typical CorrelAid project, there are **three types of team roles:**

* project lead / team lead: The project lead is a team member that has some additional responsibilities such as coordination of the team, being the primary contact person of the organization, and reporting back to the project coordinator (aka you). Usually, the project lead is also a more experienced data scientist who can help others with technical problems but this doesn't have to be the case. The project lead can also be someone who is very knowledgable and has high domain expertise.
* team member: "regular" team member: upper beginner level, mid-level and experienced data scientists / data analysts.
* team trainee: at least one position in every CorrelAid project is reserved for less experienced data scientists who are just at the start of their data science journey.

A usual CorrelAid project team looks like this:

* 1 project lead
* 2-4 team members
* 1 team trainee

Depending on the project, you can also define two project leads or team trainees, or have more "regular" team members.

#### Find a team lead early!

{% hint style="warning" %}
**When and how to find a team lead**

Ideally, you have the position of the team lead filled before sending out the call for applications. This way, they can participate in the team selection process and can already be involved in some communication with the NPO. In addition, if you know the team lead personally, they will probably be more committed to the project's success.

If you don't know anyone who could be a candidate, ask around in the core team whether someone knows someone who could be interested in the project. In CorrelAidX contexts, ask people who have attended several meetups / who you know personally.
{% endhint %}

## Call for Applications

{% hint style="warning" %}
**CorrelAidX projects**

In our Mailchimp newsletter, we have so-called _segments_ for all chapters, i.e. we can contact all CorrelAid members who are interested in activities of your CorrelAidX chapter. Usually, CorrelAidX projects should be sent out to this local newsletter list to give everyone in your area the chance to apply for the project.

However, if you are just starting out as a chapter and just acquired your first project, it is also possible to form a team out of the initial members of the chapter without sending the project over your local section of the newsletter. In this way, you can experience a CorrelAid project together and pass on your knowledge in later projects.
{% endhint %}

{% hint style="info" %}
**Relevant CorrelAid actors**

* project coordinator
* project lead (if already found)
{% endhint %}

#### Checklist

{% hint style="success" %}
* [ ] draft call for applications on Google Docs or CodiMD
* [ ] get approval for call for applications from NPO
* [ ] add project to kobotoolbox form
* [ ] send out call for applications to newsletter
* [ ] (if necessary), send out reminder to newsletter
{% endhint %}

### Draft the call for applications on CodiMD

Once you have decided together with the NPO that a project makes sense and you have a clear idea of the scope and content of the project, you can start drafting the call for applications (de: Projektausschreibung). The call for applications is the central way how we announce our projects and how we collect applications from our network.

You can draft the call for applications on Google Docs or CodiMD. In order to make this as easy as possible for you, we provide [templates](https://drive.google.com/drive/u/0/folders/1KR7dxTdLRhtDEsQspLnEEtA2vsYM7gan) for this that closely mirror the structure of the Mailchimp template that you'll use later to send it out to the network.

**Copy the content of the Google Template into a new Google doc (or create a new doc from the template) or CodiMD and rename it to reflect your project's name.** Then you can start filling in the necessary information.

{% hint style="info" %}
**German or English?**

This depends on the project. To be as inclusive as possible, the English one should be the default. However, if your project will be in German only and it is _really_ not possible to participate without good German skills (i.e. because of the nature of the data), choose the German one.
{% endhint %}

### Add project to KoboToolbox form

For project applications, we have a [Kobotoolbox form](https://ee.correlaid.org/x/8ZibAmdq) that we use for all projects. At the beginning of the survey, applicants are asked to select which project they want to apply to. Hence, you need to add your project to this sign-up form. In order to do so, please contact either Nina (@Nina Hauser), Phil (@Philipp Bosch), or Frie (@frie) on Slack as they have access to Kobotoolbox.

### Send with Mailchimp

Once you're finished drafting your call for applications and have checked back with the organization to get a go-ahead, you can send it out to our network using our Mailchimp newsletter list. If you do not have access to Mailchimp, ask Frie or Phil for support.&#x20;



{% hint style="info" %}
**How can I only send to a local chapter?**

Local chapters are stored in Mailchimp as segments of the CorrelAid Newsletter audience. When building your Mailchimp campaign, you can select a specific segment of the list.&#x20;
{% endhint %}

## FAQ

{% hint style="info" %}
As always, if you have any questions, please ask in the #projects channel on Slack.
{% endhint %}
