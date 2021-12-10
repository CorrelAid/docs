# CorrelAid Data4Good projects

Our Data4Good projects are at the core of our work. In our skilled volunteering projects, we connect data scientist volunteers from our network network of over 2000 volunteers with nonprofit organisations. Through the projects, our volunteers have the opportunity to apply their existing skills and gain new knowledge. At the same time, they support nonprofit organisations with solving their data-related challenges. Over 2-6 months and in teams from 2-7 data scientists, CorrelAid volunteers have tackled diverse data challenges of nonprofits: from data collection, data visualization and exploratory data analysis to automation, reporting and advanced statistical analyses using machine learning and deep learning techniques.

## Actors

Several actors are involved in a CorrelAid Data4Good project. Here is a small overview with the most important terminology.

| Who                         | Description                                                                                                                                                                                                                                                                             |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| NPO / the organization      | our non-profit partner organization                                                                                                                                                                                                                                                     |
| Contact person              | the contact person at the NPO. Usually we have one or two contact persons who we will talk with.                                                                                                                                                                                        |
| CorrelAid                   | CorrelAid as an organization                                                                                                                                                                                                                                                            |
| Core team                   | The organizational team of CorrelAid, de facto everyone who is active on Slack                                                                                                                                                                                                          |
| Project coordinator         | member of the Core Team who oversees the project from the time of acquisition to the final follow-up. Is not part of the project team, i.e. does not do data analysis. During the project work phase, the Project Coordinator is responsible for getting updates from the project team. |
| Project lead / team lead    | Leads the implementation of the project as part and primus inter pares of the project team. Typically also actively contributes to code or other outputs of the project (not solely 'team management' role).                                                                            |
| Project team / team members | Volunteers of the CorrelAid network who are involved in the implementation of the project                                                                                                                                                                                               |
| team trainee                | a team member who is not as experienced yet.                                                                                                                                                                                                                                            |

## Project phases

A typical CorrelAid project goes through 6 stages. Those are sketched out here to give a high-level overview. More detailed content can be found in the rest of the manual.

#### First contact / Project acquisition

CorrelAid has come in contact with a potential partner organization / NPO:

* they've contacted us over email
* we have met them at an event
* we have approached them
* someone else put us into contact with them

#### Ideation

The project coordinator has established communication with the organization. Together with the contact person(s) from the NPO, they figure out whether and if so, how CorrelAid volunteers could support the NPO with their data challenge. Based on this information, the project coordinator develops the project call for applications in close coordination with the contact person(s) of the NPO.

{% content-ref url="project-coordinators/ideation.md" %}
[ideation.md](project-coordinators/ideation.md)
{% endcontent-ref %}

#### Team selection

The project coordinator sends out the call for applications via the newsletter and collects the applications. Once the application deadline has passed, the project coordinator looks for a selection committee who then select a team.

{% content-ref url="project-coordinators/team-selection.md" %}
[team-selection.md](project-coordinators/team-selection.md)
{% endcontent-ref %}

#### Onboarding

The project lead together with the project coordinator and the support of the relevant tool administrators sets up the project tooling and communication channels. The project coordinator together with the project lead and the NPO starts planning the kickoff.

{% content-ref url="project-coordinators/onboarding.md" %}
[onboarding.md](project-coordinators/onboarding.md)
{% endcontent-ref %}

#### Kickoff

The kickoff marks the official start of the project. Here, the NPO, the project coordinator, the project lead and the project team come together for a weekend (or an online event) to get to know each other, learn more about the background of the project and plan the project.

{% content-ref url="project-coordinators/kickoff.md" %}
[kickoff.md](project-coordinators/kickoff.md)
{% endcontent-ref %}

#### Project work

The project team works on the project, with regular feedback loops with the organization. The project team leader leads the team as primus inter pares and is responsible for keeping the project running. From time to time, the team gives an update to the project coordinator to ensure that no problems exist and that the project is running smoothly.

{% content-ref url="project-coordinators/project-work.md" %}
[project-work.md](project-coordinators/project-work.md)
{% endcontent-ref %}

#### Handover

The project team hands over the finished analysis / visualization / .. to the NPO.

{% content-ref url="project-coordinators/handover-workshop.md" %}
[handover-workshop.md](project-coordinators/handover-workshop.md)
{% endcontent-ref %}

#### Follow-up

Feedback is collected by the project coordinator from both the NPO and the project team members.

{% content-ref url="project-coordinators/follow-up.md" %}
[follow-up.md](project-coordinators/follow-up.md)
{% endcontent-ref %}

## Actors in project phases

|                     | Ideation & Call for Applications | Team selection | Onboarding & Kickoff | Project work | Handover  | Follow-up |
| ------------------- | -------------------------------- | -------------- | -------------------- | ------------ | --------- | --------- |
| NPO                 | ✅                                |                | ✅                    | ✅            | ✅         | ✅         |
| Project coordinator | ✅                                | ✅              | ✅                    | 🟨$$^1$$     | 🟨 $$^1$$ | ✅         |
| Project lead        | 🟨 $$^2$$                        | 🟨 $$^2$$      | ✅                    | ✅            | ✅         | ✅         |
| Selection committee |                                  | ✅              |                      |              |           |           |
| Project team        |                                  |                | ✅                    | ✅            | ✅         | ✅         |

✅: involved

🟨: optional / in reduced capacity

* $$^1$$ during the project work phase, the project coordinator regularly checks in with the project team to make sure everything is going smoothly. They are also available for support.
* $$^2$$ Ideally the project coordinator should find a project team lead during the ideation phase by directly asking people whether they'd be interested in the role. In this case, the team lead can be involved in the ideation and team selection processes.

## FAQ

### I am applying for a project through the form and I am unsure which role to choose. Help!? <a href="#which-project-role" id="which-project-role"></a>

**Team Lead:** As a team lead, you lead the implementation of the project as part and primus inter pares of the project team. In addition, you have some organizational tasks: Together with your team mates, you agree on an internal organization of your team, e.g. how often you have check-ins, how to organize the repository, how to keep track of progress, how often to talk to the NPO partner organization etc. Of course, you are not solely responsible for implementing those decisions but organize the team to be able to do so. Note: you do not need to be a technical expert to be a team lead, it is more about organizing a team and facilitating and following up on discussions.

**Team member:** You are able to structure your own work and learn new technologies and tools (mostly) on your own. This doesn't mean that you can't have questions for your team mates or prefer learning/working together with someone else - especially when dealing with technologies/techniques that are new to you. But in contrast to a team trainee, you are confident in finding resources that will help you and acquiring knowledge on your own.

**Team trainee:** As a team trainee, you do not have much experience with most of the technical tools that are used in the project and/or you only have very little experience with data analysis projects. You'll probably need a lot of support from your fellow team members, e.g. in setting up the project on your laptop or finding tasks that fit your skills (e.g. small data cleaning tasks). Note: you are not automatically a team trainee if this is your first CorrelAid project.

**If you are still unsure which role to choose, choose the one which feels most appropriate and write a sentence in one of the open text fields that you were unsure.**&#x20;

### **I am applying for a project through the form and don't understand the experience scale. Help?!** <a href="#experience-scale" id="experience-scale"></a>

Beginner = I have never done this before / I have never written a single line of code.\
User = I have gained some first experience in this field / I have written code on my own.\
Advanced = I have gained some experience / I have written complex scripts\
Expert = I know my way around very well / I write my own functions and packages.

***
