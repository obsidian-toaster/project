# Table of Contents  
[Introduction](#introduction)
[Tools](#tools)
[Communication](#communication)
[Workflows](#workflows)

<a name="introduction"/>
# Introduction

This document describes and details :
- The tools that we will use to communicate together, to manage and organize the non-technical tasks using kanban view with Trello and technical tasks using Jira Scrum View with sprints.
- Procedures and their corresponding workflows to manage the PRD user stories, the ERDs and correlated tasks
- Principes to adopt to better communicate/discuss together

# Tools

The management of the tasks (meeting request, user story discussion, ...) that the Obsidian project will generate will be simplified by adopting the following tools.
Some will be only used to communicate (IRC), start a call (Bluejeans, Skype), Share a screen or Google Doc documents while others will help to handle the tasks, organize them or plan using 
the scrum methodology the sprints to deliver the Obsidian Deliverables.

## Task/Issue Management 

* [Trello](https://trello.com/b/DI2J0MHN/obsidian) : Non Technical Tasks & Planning Tool
* [JIRA](https://issues.jboss.org/projects/OBST/summary) : Tickets & Scrum Management Tool

### How to use Trello 

You can find more info about how to use Trello as presented by OpenShift Team hereafter

- https://trello.com/b/22FjgidH/how-we-use-trello
- https://trello.com/c/FmXGaXIj/56-getting-started-how-we-use-trello

The Trello boards will be used to manage the non technical tasks related to a project. The "generator by example" which corresponds to a deliverable of obsidian can be assimilated to a project like vert.x, swarm, EAP, etc.
The board which is a kanban view will help us to figure out what should be tracked, included into a sprint or not, discussed, reviewed.... It could be possible that some tasks will not been linked to a JIRA or Github issue 
as they correspond to a request to create a document, contact a group, team, configure a machine, ... or could be used to translate a user story to ERD response which contains sometimes link(s) to jira/bugzilla/...
(example : https://trello.com/b/wqe9UaaZ/developer-experience)

### How to create a card

A trello card can be created directly within an Obsidian board (https://trello.com/b/DI2J0MHN/obsidian, ...) or from GMail. In that case, the following Chrome extension ("https://chrome.google.com/webstore/detail/gmail-to-trello/oceoildfbiaeclndnjknjpfaoofeekgl")
should be installed. When you will create a card from an email, you can select the board and the list "New" where the card should be created.
 
Remark : Please use preferentially the list "New". That will allow the members part of the board to review it during their weekly call as the "new" listed cards will be accepted/refused, assigned to member(s)
and a due date defined. The due dates will allow the Project/Program Managers, using the power-ups "calendar" app, to take actions when the due dates are overpassed.

## Communication Tool

* [Slack](https://microservicesplatform.slack.com/messages) : IRC channels, notifications platform

Slack's remarks :

* Slack channels can be accessed using an IRC client with the IRC or XMPP over SSL protocols. You can get your user/password at this address like also more information about
  how to configure your client : https://microservicesplatform.slack.com/account/gateways
* A Skype or Bluejeans call can be started within a slack channel using /bluejeans [id] or /skype call commands.  
* [Screenhero](https://screenhero.com/) which is  "collaborative screen sharing app" is integrated too with Slack like github
* Drop Box & Google Drive documents can be shared directly using Slack.

<a name="comunication"/>
# Members's communication

This section will detail how to proceed to communicate between the members of the project concerning the topics which are highlighted hereafter:

## Question/Ping me

For simple process where you would like to contact a project's member, question it, please use the slack IRC team (https://microservicesplatform.slack.com/) and its corresponding channel.
If, by example, you would like to ask a question about the "Generator", then you can use the #generator channel. Here is the list of the channels created and their description:
                                                                                                                 
* 1-Generator : Code generator tool designed using JBoss Forge & JS Front
* 2-SpringBoot : Spring Boot & JWS
* 3-vertx : Productization of Vert.x for OpenShift
* 4-swarm : Productization of WildFly Swarm for OpenShift
* 5-Documentation: Discuss quickstarts, documentation to be deveoped (dev, installation guides)
* 6-OpenShift : S2I, CI/CD, Go client, Web Console, Services (metrics, logging)
* wk-group : Working Group
* general : General channel to discuss Obsidian related questions/issues
* projet : Channel to be used by Product Manager, Project Manager and Program Manager. Trello notifications are published here
* notification : where bot integration will take place (github, ...)

The channels starting with a difit number corresponds to a deliverable/scrum team

## Discussion

When a topic, which have been started as a question or discussion, will require that:

- Multiple participants are involved to provide their advise in order to answer to the question,
- Somebody investigates and makes some research,
- A formal approval is needed

then, it makes more sense in this case to create a Trello card under the list "New" of the corresponding board (generator, vertx, springboot, swarm, ...).
During the weekly calls, the card will be discussed, reviewed (approved,rejected), assigned to a resource wirh a due date.

As the discussion could become an idea, a new user story or a task to be implemented, acting as such will allow to keep track of the request and potentially include it as a milestone
to be delivered for a version of Obsidian and manage it within a Jira sprint.

## Announce

The Obsidian Engineers/PM Mailing List should be used to communicate the agenda, minutes of the bi-weekly meeting, to publish general announces or changes but never to start a discussion
. This channel could also be used to prepare the sprint or communicate the project milestones. 

When an email about a meeting is published on the Obsidian Mailing List and that you want to participate or to invite somebody, please use this procedure :
@AI: I would like to ask you to nominate yourself for the call and forward this email to anyone you know should be aware. We will invite them and add them to the obsidian-pm-list as well.
 
## Meeting minutes

When a meeting will take place between Obsidian's members, it could be required that minute meeting document is created. The template to be used to generate the minutes is described hereafter.
The Obsidian minutes will be stored within the following Google Driver folder : https://drive.google.com/open?id=0B6OzT-mciDmoQ0NkUDUxcmtFSUE

Remark : An example about such minute is posted here : https://docs.google.com/document/d/1SJJod6qi5i1_w50BwR98H6RIN2X_qK81wf0_ts63wfg

```
Minutes - [dd MM YYYY]

Participants : [firstname lastname, firstname lastname, firstname lastname, ...]
________________________________________________________________________________

A) Points (to be) discussed

* Point A
** Sub point A
** Sub point B
** Sub point C
... 
** Point B 

Remarks :
- As you can see the title includes text between parenthesis. That indicates the fact that this minutes doc can also be used during the meeting and
  when the minutes are will be prepared for publication, then you can skip this part between parenthesis.
- A point & sub-point must include the acronym of the user reporting it (e.g. Setup the working group - CHM) using the following
  convention (first 2 letters of the firstname followed by the first letter of the surname.
- If a ticket (jira/github) or Trello Card exist, then they should be mentioned.
- A collection of Trello cards grouped can be used instead of the points to be discussed
____________________________________________________________________________________________

Decisions

* Item 1
* Item 2
* Item 3

Remark :
- An item could or should be converted into a Trello card, added to a board within the New list
________________________________________________________________________________________________

Next Steps

@User: TBD
@All: TBD

Remark :
- The "Next Steps" section includes the future tasks to be done, most probably to be covered into another meeting
- Like the "decisions", they can be defined as Trello cards where the user assigned is mentioned  
```

<a name="workflows"/>
# Workflows

To generate a deliverable from a Product Definition which contains user stories, it is important to follow some workflows in order to manage correctly the tasks/actions required as they will
allow the actors, part of the process, to code, test, document and finally deliver a product which corresponds to the sum of the deliverables defined within the roadmap for a specific version. 

To achieve this goal, multiple actions or tasks will be created and should be managed appropriately. Some, that we will categorize as non-technical, will be managed using the Trello Tool and boards
while the others will be handled using JIRA and Scrum views.

The non-technical tasks corresponds to a request (contact a person, organize a meeting, ...) or an action (configure, a setup a machine, ...).
The motivation to use Trello and not JIRA is that several actors prefer to use a more simple/agile tool where an action/task could be created from an email, that some tasks doesn't require to have a corresponding
JIRA ticket or even GitHub issue, that some requests will be assigned to groups/teams which are using Trello or even Github to handle their tasks, ...

## Non Technical Request

Multiple boards have been created for the Obsidian project and each correspond to a specific deliverable, project to be managed. Here is the list and their description :

- [Obsidian](https://trello.com/b/DI2J0MHN/obsidian) : Board used by the Program Manager, Project & Product Manager
- [Obsidian Spring Boot JWS](https://trello.com/b/70ZIY4Va/obsidian-springboot-jws) : Board to discuss SpringBoot & JWS related stuffs
- [Obsidian - Vert.x](https://trello.com/b/n4AHYysk/obsidian-vert-x) : Eclipse Vert.xproductization on OpenShift 
- [Obsidian - Generator](https://trello.com/b/hhWz5leK/obsidian-generator) : Code Generator Tool & Maven Integration
- [Obsidian - WildFly Swarm]() : WildFly Swarm productization on OpenShift 
- [Obsidian - Documentation](https://trello.com/b/2ZsLAdWT/obsidian-documentation) : Developer/Installation guide & Quickstarts

These are the expected lists part of each board

**New -> Backlog -> In Progress -> Complete**

There are several things that make a team board "well formed."  It's important to keep them consistent across the teams so that any stakeholder can go to any board and understand how the team is operating and where they are in the process.

**New**

The flow is from left to right. Each card starts in "New", goes through a grooming process of making sure a card is well formed.  The description should be one line and a comment should exist that describes what the task in more detail - enough detail that a level of effort can be assigned.

No user member should be assigned to the card, nevertheless the author of the card should include its acronym within the title of the card. If a document exists, include the link of the document within the card created. If a card has a specific due date, you can specify within the description about the card.
 
**Backlog**

During the weekly meeting, the team will review the "New" cards and moves cards into the Backlog list, which is in a roughly prioritized order. During the grooming process the card will be assigned to member(s) like a due date.

**InProgress**
The card is moved to the list "InProgress" when the member assigned will start to work on it.

**Complete**
When a member finishes the item, they will move it to the Complete list.

Remark : If the content of the list "Complete" becomes too big, then an archived list could be created to move the most olders.
 
[TODO - Add definition about the labels]

## PRD & User stories

The product document contains a list of user stories which are not categorized but prioritized in a certain way as some user stories are mandatory (= must, will) while others are optional (= should, could).
Moreover, they are not associated to a specific roadmap release as the process to quantity the workload to develop the user story, to investigate its feasibility & acknowledge it hasn't been yet done.

To deal with this process, the following workflow has been designed using the Trello Board "Obsidian - Product"
  
**New -> Review -> Accepted OR Refused -> Working-Group Board (optional) -> Release**  

**New**

The flow is from left to right. Each card starts in "New" goes through a discussion process where the user story will be discussed by the engineers board with the product manager. The discussion will allow to better understand
the request about the user story, improve its description, request additional infos from the Product Manager, prioritize it and decide in which version of the product it will be released. When this process has been done, then the user 
story can be moved to the next list to start the "Reviewing" process
 
Remark: 

- We should start the discussion with the "New" list at the condition that we get enough user stories to cover a **MVP**
- By splitting the content of the PRD document into a list of user stories, we will simplify the reviewing/questioning & commenting process instead to use one Google document !

**Review**

When a user story is added to the list "Review", then the engineers can start the process to review the feasibility of the request and if we will accept/refuse it. Ideally this reviewing process should be done by the architect
with the engineers responsible about the technology to be developed. As with the "New" list, it is still possible during the reviewing step to question/comment the user story and ask additional information from the Product Manager.
Finally, they will decide if the user story is accepted or refused. In both cases, it is important to motivate the decision and to inform the Product Manager.

Optionally, the task/Card could be moved to the Board Working Group as it will be discussed hereafter.
 
**Accepted**

The accepted user story will move to this list where the user will tag the user story with the labels corresponding to the deliverables to be designed (e.g : doc = documentation, dev = development & testing, vertx, swarm, generator, ...).

**Refused**

The Product Manager will review the refused user story and could, based on the decision taken by the engineers, make a new proposition by moving the card to the "New list". In this case, the card must be tagged with the info (maybe using a custom field)
"refused" to inform the members.

**Optional - Working Group**

When a user story will request to be discussed by a working group / task force, then the card will be moved to the board "Obsidian Working Group" under the list "New". This step will be sometimes required when the user story 
is related to a feature which is transverse (e.g. : Support the streaming of a database, hot deployment of ConfigMap, ...) and will require the assistance of persons working for different units (Middleware, OpenShift, ...). 
At the end of the "research" work, the task will come back to the original board with a proposition and maybe a solution to implement the user story. 

**Release x.y.z**

When the user story has been accepted, then it can move to the "Release x.y.z" list which corresponds according to the roadmap to the version where we target to deliver the user story. The release number is represented by the convention x.y.z.
With such information, the ERD work could take place.

For each user story defined, an ERD card will be prepared containing the description about the proposition and a link to a document including the technical information required to develop the feature. Such Google Doc should contain
different sections covering the following topics: High Level Architecture, Technology/Frameworks used & versions, Diagrams (sequence, class, ...) supporting the description about the feature.

Remark : The rule to be followed when the ERD is developed will be that it should be considered as a unit of work or unit of delivery. If it will require multiple deliveries (documentation, development, ...) then it should be splitted
 in multiple units and referenced as such within the Release list.

## ERD Management & Sprints

The process starts when the scrum master with its team will review the ERDs to be developed. They will create the corresponding JIRA tickets, assign them to the resources, calculate the points in order to include them within the sprint which corresponds to a cycle of x weeks that they will have to develop the ERDs selected.

At the end of the sprint effort, then the Scrum master will report to the Product & engineers manager Trello board what it has been able to develop during this period of time.

Then, a discussion will take place to investigate what will be done according to the release defined. Two cases are possibles; the ERDs defined within a specific release have been developed successfully within a sprint and the release
can move to QE/Prod. The release is incomplete and then it is required to reassign the ERDs non developed to a subsequent release.

[TODO - Describe JIRA Scrum & Sprints]

[TODO - Describe How we will work with QE & Prod to involved them within the workflow]
