# Team selection

{% hint style="info" %}
**Relevant CorrelAid actors**

* project coordinator
* project team lead \(if already found\)
* selection committee
{% endhint %}

#### **Goals**

1. find a diverse, capable team

#### Checklist

{% hint style="success" %}
* [ ] find a selection commitee 
* [ ] anonymize applications \(names, email adresses\) 
* [ ] share applications with committee
* [ ] team selection call
* [ ] confirm team members & send out rejection emails 
* [ ] confirm team lead
* [ ] invite team members to Slack channel 
* [ ] create [Git](../../wiki/infrastructure/github-and-gitlab.md) repository and invite members as collaborators
{% endhint %}

## Find a selection committee

After the call for applications is sent out to the network, you can start looking for a team selection committee. Usually a team selection committee consists of 3-4 members:

* the project coordinator\(s\)
* 1-2 people from the core team 
* the future team lead \(if available\)

The selection committee should be comprised so that gender parity is respected. In addition, it makes sense to include people with differing levels of experience. At least 1-2 of the members should be able to judge applications with regards to technical skills. People who have applied to the project cannot be part of the team selection committee.

You can find members for your committee by posting on Slack in \#general or \#projects. Best include some information about the project. For example:

> Do you want to be part of the team selection committee for \[PROJECT NAME\]? The project will be about training a model to do XX. It will be in Python.

## Application report

Once the deadline has expired, you should request the **anonymized application report** from Frie. She will share the anonymized data with you and the other team selection committee members as a HTML report. She will also share with you as the project coordinator the **mapping from the anonymized applicant ids to the email adresses** in a secure way so that you can later contact the applicants. We recommend not to look at those before making your selection to avoid any bias.

{% file src="../../.gitbook/assets/2030-03-exa\_applications\_report.html" caption="Example report with fake data" %}

If your project is part of the project cycle, the report will also include information on what other projects the applicants applied to.

## Team selection call

Once you have found 2-4 people, arrange with them for a video call.

Everyone should have a look at the applications before the call so that decisions can be made quicker.

Team selection criteria:

* technical and statistical skills
* interest in topic / motivation for the project
* can the person learn something on the project?

One spot in the team is reserved for a "beginner".

**Principles of team selection:**

* no discrimination based on gender, gender identity and expression, sexual orientation, disability, mental illness, neuro\(a\)typicality, physical appearance, body size, age, race, ethnicity, nationality or religion.
* at least 50% of team seats are filled with applicants with genders currently underrepresented in tech \(currently everyone who's not a cisgender man; cisgender = people whose gender identity matches their sex assigned at birth\)
* applicants belonging to groups currently underrepresented in tech should be preferred whenever possible
* people who have unsuccessfully applied to a project in the past should be preferably considered whenever possible 
* people who apply for the first time should be preferably considered compared to people who have already participated in a project 
* unless in specific circumstances, interviews with applicants are not conducted 
* the selection committee tries to come to a consensus decision. If a consensus cannot be reached, the majority decides. If there is no majority, the project coordinator decides. 

{% hint style="info" %}
**Helpful guidelines: team roles**

When making a selection, the selection committee should aim to select people who have different areas of expertise so that they can help out each other. Here are some unofficial team "roles" that can be useful to think about when selecting team members \(they are not mandatory to fill, just a tool to help you think about the requirements of a project\):

* methods specialist: this is someone who has a high \(theoretical\) expertise in statistical and machine learning methods that are relevant to the project. They can give input when deciding on which model to use for specific use case. 
* programmer: they are quite experienced in the programming language used for the project and know different tooling and best practices that will help with code quality \(e.g. how to setup a Python project\). Ideally, this person is also quite good at git and can help other team members with merge conflicts and other git problems.
* domain specialist: this person already knows a lot about the domain of the project \(e.g. they've worked a lot with environmental data\). They can give valuable input about the intricacies of the problem at hand. 
* data wrangler: this person is quite good at and enjoys cleaning and wrangling all sorts of data. They can speed up the process in the beginning of the project to get to a state where  analysis / modelling / visualization can be done.

**Things to look for in all applications:**

* motivation: is the sole motivation the technical challenge? Ideally, project members should also be intrinsically motivated to help the NPO.
{% endhint %}

## Confirming team members

Before you send out rejection emails to all those applicants who were not selected for the team you should make sure that everyone is still interested in participating in the project. After all, 1-3 weeks might have passed since they applied and they could've changed their minds. You can use the acceptance email template to get the confirmation.

After everyone has confirmed their interest, you can send out the emails to the applicants who could not be considered. You can use the rejection email template to do this. If you want to send out multiple rejections at once, please make sure to **use blind copy** \(BCC\).

### Acceptance Email

{% tabs %}
{% tab title="🇬🇧" %}
Subject: \[CorrelAid\] Your application for the project "\[Project name\]"

Dear \[name applicant\],

Thank you for your interest in participating in our project with \[Organisation\]. We are happy to inform you that you were selected to be part of the team.

Please quickly let us know whether you're still interested in participating in the project so that we can send out emails to those who could not be considered this time.

As a next step, we will send you an invitation to our Slack workspace and add you to the project channel \[\#slack channel name\]. There, you'll get to know the rest of the team and we will coordinate the rest of the onboarding process so that you can get to coding as soon as possible.

Looking forward to the project!

Best regards,

\[project coordinator\]
{% endtab %}

{% tab title="🇩🇪" %}
Betreff: \[CorrelAid\] Deine Bewerbung auf das Projekt “\[Projektname\]”

Liebe:r \[Vorname Bewerberin\],

vielen Dank für dein Interesse, an unserem Projekt mit \[Organisation\] mitzuarbeiten. Wir freuen uns, dir mitteilen zu können, dass du als Teil des Teams ausgewählt wurdest!

Es wäre super, wenn du schnell bestätigen könntest, dass du immer noch Interesse an dem Projekt hast. Dann können wir Emails an diejenigen verschicken, die dieses Mal leider nicht berücksichtigt werden konnten.

Als nächstes werden wir dir eine Einladung zu unserem Slack Workspace schicken und dich dem Projekt-Channel \(\[\#channel name\]\) hinzufügen. Dort lernst du den Rest des Teams kennen und wir können alle weiteren Schritte des Onboarding-Prozesses koordinieren, sodass ihr so schnell wie möglich zum Coden kommen könnt!

Ich freue mich auf das Projekt!

Viele Grüße,

\[Projektkoordinator:in\]
{% endtab %}
{% endtabs %}

### Rejection Email

{% tabs %}
{% tab title="🇬🇧 " %}
Subject: \[CorrelAid\] Your application for the project "\[Project name\]"

Dear \[name applicant\],

Thank you for your interest in participating in our project with \[Organisation\]. We were very happy about the applications we received. Unfortunately, the amount of applications \(there were \[number of applications\]\) meant that we had to make a selection.

Unfortunately you are not part of this project. You should not take this as a negative evaluation of your person or your skills. A variety of criteria played a role in our selection - we did not solely select the best-skilled applicants but aimed to put together a team with diverse experiences, skillsets and interests.

Of course, more projects are already in our pipeline and when making our selection, we also take into account whether analysts had unsuccessfully applied to a project in the past. So be sure to mention in your next application that you were not selected for this project. The next opportunity to work on a project will certainly come soon.

In the meantime, please feel free to contact me with questions and ideas at any time.

Best regards

\[Project coordinator\]
{% endtab %}

{% tab title="🇩🇪" %}
Liebe:r \[Name Bewerberin\],

vielen Dank für dein Interesse, an unserem Projekt mit \[Organisation\] mitzuarbeiten. Wir haben uns über die Resonanz, die wir erhalten haben, sehr gefreut. Leider bringt die Vielzahl an Rückmeldungen \(\[Zahl der Bewerbungen\] an der Zahl\) mit sich, dass wir eine Auswahl treffen mussten.

Leider bist du bei diesem Projekt nicht dabei. Das solltest du keinesfalls als negative Wertung deiner Skills oder deiner Person betrachten. Bei unserer Auswahl haben eine Vielzahl an Kriterien eine Rolle gespielt - so haben wir auch darauf geachtet, dass wir eben nicht nur nach den besten Kenntnissen auswählen, sondern ein Team mit vielfältigen Erfahrungen und Interessen zusammenstellen.

Diesem Projekt werden bald weitere Projekte folgen. Bei der Auswahl berücksichtigen wir auch, ob Analyst\*innen in der Vergangenheit leider nicht zum Zuge kamen. Erwähne daher unbedingt bei deiner nächsten Bewerbung, dass du bei diesem Projekt nicht zum Zuge gekommen bist. Die nächste Möglichkeit zur Projektmitarbeit kommmt sicher bald.

In der Zwischenzeit kannst du dich gerne jederzeit an mich wenden.

Herzliche Grüße

\[Projektkoordinatorin\]
{% endtab %}
{% endtabs %}

## Confirming team lead

### Promoting a team member/team trainee

{% tabs %}
{% tab title="🇬🇧 " %}
Hi NAME,

my name is \[XY\] and I am one of the project coordinators for the CorrelAid project with \[ORGANIZATION\] which you also applied to and were selected for. :\)

When doing the team selection, we were quite impressed by your application and we wanted to ask you whether you would be interested in becoming a team lead for the project? 

The team lead position can be described as follows:

As a team lead, you lead the implementation of the project as part and primus inter pares of the project team. In addition, you have some organizational tasks: Together with your team mates, you agree on an internal organization of your team, e.g. how often you have check-ins, how to organize the repository, how to keep track of progress, how often to talk to the NPO partner organization etc. Of course, you are not solely responsible for implementing those decisions but organize the team to be able to do so. Note: you do not need to be a technical expert to be a team lead, it is more about organizing a team and facilitating and following up on discussions. 

We think that your \[QUALIFICATIONS/EXPERIENCES\] greatly qualify you for that role!

Of course, we as the project coordinators would support you and would also have a call before the kickoff to answer any questions and give you more information about the tools and methods that we have prepared for team leads. :\) 

If you are still unsure and would like to discuss this further before making a decision, we are available for a call \[INSERT TIME\]. Of course, it's also totally ok if you'd rather participate in the role you originally applied to!

Best,

\[PROJECT COORDINATORS\]
{% endtab %}

{% tab title="🇩🇪" %}

{% endtab %}
{% endtabs %}



