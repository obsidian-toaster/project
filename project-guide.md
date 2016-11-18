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

[Obsidian](https://trello.com/b/DI2J0MHN/obsidian) : Board used by the Program Manager, Project & Product Manager
[Obsidian Spring Boot JWS](https://trello.com/b/70ZIY4Va/obsidian-springboot-jws) : Board to discuss SpringBoot & JWS related stuffs
[Obsidian - Vert.x](https://trello.com/b/n4AHYysk/obsidian-vert-x) : Eclipse Vert.xproductization on OpenShift 
[Obsidian - Generator](https://trello.com/b/hhWz5leK/obsidian-generator) : Code Generator Tool & Maven Integration
[Obsidian - WildFly Swarm]() : WildFly Swarm productization on OpenShift 
[Obsidian - Documentation](https://trello.com/b/2ZsLAdWT/obsidian-documentation) : Developer/Installation guide & Quickstarts

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

Use cases will move to "New" list -> Review

## ERD Management

## Scrum/Sprint

THIS IS ANOTHER TEST

cmoulliard	[10:13 AM]  
The biggest issue/challenge concerns how to manage the comments/remarks. The way that it has been addressed by John for the PRD was a mess. I have warned John that we can't manage correctly all the comments/remarks correctly using google doc when we have too many members

hbraun	[10:27 AM]  
I think the PRD/ERD feedback would need to be consolidated prior to sending it back into the process

[10:28]  
i see two possible ways: a) following the formal structures (per team, i.e. Swarm, Vert.x, etc) or b) following the WG structures (cross unit)

cmoulliard	[10:28 AM]  
I agree but it is also important to define how we will manage / collect remarks - comments

hbraun	[10:29 AM]  
documents per unit

[10:29]  
regardless if a unit is a project team or working group

[10:29]  
one consolidated document per unit

[10:29]  
that would be good

cmoulliard	[10:30 AM]  
So you suggest to decompose the "monolithic" PRD doc into "Microservices" ERD -  units :wink:

hbraun	[10:30 AM]  
:slightly_smiling_face: kind of

[10:30]  
yes

[10:30]  
you actually do the same already: different slack channels for different work areas

cmoulliard	[10:30 AM]  
That was my idea too.

hbraun	[10:31 AM]  
i think the PRD/ERD process could follow that structure quiet naturally

cmoulliard	[10:31 AM]  
A unit = deliverable (generator, vertx, springboot, swarm, ...) = slack channel

hbraun	[10:31 AM]  
yes

[10:32]  
but it could as well be a nested hierarchy: unit “runtimes”, within “swarm, vert.x, springboot"

[10:32]  
i think the PRD discussion on the level of “runtimes” are more beneficial then having each team within that unit discuss the PRD separetly

[10:33]  
most of the requirements are cross cutting already

[10:33]  
and the ones specific to vert.x or swarm can still be dealt with at the lower level, in each projectteam

[10:34]  
actually I believe that the implementation  phase could follow these structures as well: we probably have a lot of cross cutting functional requirements

[10:35]  
i’ve also discussed this approach with our QE: there is a good chance that a large part of the test suites can be used across the runtimes

cmoulliard	[10:35 AM]  
This is why maybe the approach to transpose the PRD user stories into a collection of jira tickets or trello cards is perhaps more interesting as a ticket/card can have different labels in or to be discussed crossed teams. Example: hot redeploy of configMap

hbraun	[10:35 AM]  
yes

cmoulliard	[10:36 AM]  
Good to see that we are on the same page.

hbraun	[10:36 AM]  
the question is at point to transpose the PRD into Jira tickets

[10:36]  
it looks like Jiri already requested a Jira instance with the JBEAP setup

[10:36]  
which is a good starting point

[10:37]  
are you faimilar with the JBEAP setup?

cmoulliard	[10:37 AM]  
As we can link a trello card to a document (= containing the more elaborated description) then that should simplify our life (but not from a PM point of view as we will have more tasks to track) to track, follow, vote for its implementatio, include it in a sprint ...

[10:37]  
What is JBEAP ?

hbraun	[10:37 AM]  
JBoss EAP

[10:37]  
JBEAP is the JIRA project name

cmoulliard	[10:38 AM]  
And our project will be also integrated with github PR workflow - correct ?

hbraun	[10:38 AM]  
The EAP uses a kanban approach,similar to Trello. It just resides within Jira and easily be linked to project tasks

[10:38]  
at some level yes, but not at the top

[10:39]  
to manage the requirements (PRD) dedicated Jira project is used

cmoulliard	[10:39 AM]  
As tasks will be assigned to third party projects as Almighty, Fabric8, OpenShift, I'm not sure that it will be possible to track everything using JIRA

hbraun	[10:39 AM]  
project tasks are then created in each project spearately (i.e. Swarm jira))

[10:39]  
well, we could at least track the requirements

[10:40]  
let me show you an example

[10:40]  
do you have access to this ? https://issues.jboss.org/secure/RapidBoard.jspa?rapidView=3344&projectKey=JBEAP

cmoulliard	[10:40 AM]  
This is my idea too. When a user story is translated into a ERD requirement, then we will finally decompose it into a series of x jira tickets or github issues.

hbraun	[10:41 AM]  
yes, so in your terms and tanslated to the JBEAP approach, a user story would be managed in one dedicated Jira project

[10:42]  
actual project work in separate issues trackers (jira or not) and linked to the requirements

cmoulliard	[10:42 AM]  
I have access

hbraun	[10:43 AM]  
as you can see it’s actually similar to trello

[10:43]  
so we could manage the requirements PRD this way

cmoulliard	[10:43 AM]  
My idea is to use Trello as a Global Tasks Manager to allow the PM (= Program Manager & Project Managers) to have a view about project status/progression.

hbraun	[10:43 AM]  
and the the overall schedule (Obsidian 1.0, 1.1)

[10:43]  
that’s good yes

[10:44]  
but for the functional requirements i would suggest Jira

cmoulliard	[10:44 AM]  
Here is what I will suggest to do to handle the roadmap --> https://trello.com/b/nlLwlKoz/atomicopenshift-roadmap
 Trello
AtomicOpenShift Roadmap
Trello is the visual collaboration platform that gives teams perspective on projects. Use Trello to collaborate, communicate and coordinate on all of your projects. 
 
 

[10:45]  
of course, the technical requirements (= related to the code or a function to be developed or doc to be created) will be managed using jira or github as we should keep track of the code change.

hbraun	[10:46 AM]  
so we you say “transpose PRD items into X”

[10:46]  
is X trello or Jira from your point of view

[10:46]  
?

cmoulliard	[10:47 AM]  
Trello will be used as spring/scrum view to define the tasks planned for a sprint and their related tasks = tickets which are  managed using jira.

[10:48]  
Let's talk about a dummy example where we will start with a user story defined within the PRD to see how we will manage it (PRD -> ERD -> Ticket -> Sprint)

hbraun	[10:48 AM]  
ah, i think that’s different from what’s written here: https://github.com/obsidian-toaster/project/blob/master/code-of-conduce.md
 GitHub
obsidian-toaster/project
Global information about the project Obsidian Toaster 
 
 

cmoulliard	[10:49 AM]  
What is different from code of conduct ?

hbraun	[10:49 AM]  
it mentions Jira OBST, which i thought of as being the base for managing the PRD items

[10:49]  
and roadmaps

cmoulliard	[10:49 AM]  
We haven't yet define/decided what we will create as tickets into jira

hbraun	[10:50 AM]  
maybe that’s something you need to discuss with Jiri

[10:51]  
I assumed it’s the case because the "Starting schema: JBEAP without CDW” implies a Jira project to be used "as spring/scrum view to define the tasks planned for a sprint and their related tasks"

cmoulliard	[10:51 AM]  
PRD = google doc containing user stories ==> we will decompose it as a collection of UC (= Use case) using a convention UC-OBST-1 ....

[10:53]  
The UC will be added as Trello cards (Why = a use case is perhaps related to many requirements which are potentially cross-teams) and a doc attached to the UC to describe it. The doc could be created using Google Doc or Mardown/Asciidoctor in GitHub

hbraun	[10:54 AM]  
yes, i understand

[10:54]  
it makes sense

cmoulliard	[10:54 AM]  
Next we will create in JIRA the associated/related tickets that each scrum master will manage with its team/group. For the weekly call, it will be required that the scrum master reports to Trello the progression about the use case realisation

[10:55]  
So I will add a new field for the card to be created containing the "% of completion" as we use with MS Project or smarsheet

hbraun	[10:56 AM]  
i see. sounds like a reasonable approach

[10:56]  
but what’s the purpose of the Jira project OBST then?

cmoulliard	[10:57 AM]  
Base on what we are discussing now, my vision is changing a little bit as the Trello board will be used to manage the obsidian roadmap and the use cases to be implemented while jira = scrum view, ...

hbraun	[10:58 AM]  
i think both tools jira and trello can serve this purpose

[10:58]  
but I know that jira is integrated with a lot of PGM’s reporting tools

[10:58]  
not sure if that’s the case for trello

[10:59]  
what are jiri’s thought's on this?

cmoulliard	[10:59 AM]  
Trello board = collection of cards = collection of use cases to be implemented / release (= obsidian 1.0, ...) / unit (= vertx., swarm, ...) where we can measure the project progression. The JIRA scrum view will be used by each scrum master to manage the tickets/resources assigned to each ticket,

[10:59]  
Jiri is ill this week. so we haven't yet discussed the overall approach that I'm developing here with you

hbraun	[11:01 AM]  
wouldn’t it be easier to use one tool for managing use cases, do the scheduling, reporting and manage the project tasks?

[11:01]  
i mean what’s the benefit/downside of having to use both trello and jira

[11:03]  
at the very bottom of things to manage are the projects (swarm, vert.x, openshift, etc)

[11:03]  
it looks like these different approaches to manage their projects already: github issues, jira, etc

[11:04]  
so from this point of view managing all PGM, PM work in trello is probably fine (edited)

cmoulliard	[11:11 AM]  
Project managers will use Trello while engineers/scrum master JIRA/Github. As some tasks will never become JIRA tickets or will be only discussed with Product/Marketing/... actors, then it makes no sense to manage everything either in JIRA or Trello. I would like to use Trello  + UC Cards as entry point with the Product Manager to stay concentrate on the user stories and to avoid to discuss the technical issues, .... Let's say that Trello will be used as coordination/planning tool while jira as implementation. The only think that PM should see within a Trello will be the requirements linked to a User Story and the % of completeness. If a question should be addressed with Product, then a card will be created but not a jira ticket. I prefer to decouple the discussion view needed with PM from the discussion view that engineers will use internally like also later on to handle bugs, ...

hbraun	[11:11 AM]  
i understand

cmoulliard	[11:12 AM]  
s/within a Trello will be/within a Trello board will be/

hbraun	[11:12 AM]  
you can actually right click edit your previous messages

cmoulliard	[11:12 AM]  
I propose this approach based on my experience as Project Manager

hbraun	[11:13 AM]  
so, trello it is for managing the UC's

[11:13]  
what about the ERD? How to comment and feedback on the PRD items?

[11:13]  
do you have decided on the contents of the ERD?

[11:16]  
here’s an example from EAP 6.1: https://mojo.redhat.com/docs/DOC-141459

[11:17]  
another one from BRMS: https://mojo.redhat.com/docs/DOC-108923

cmoulliard	[11:17 AM]  
yes. Trello = UC Board and more. If we have some comments to do, we can do that using the UC Trello card and next decide where the comment should be addressed (in an existing jira ticket, new, ...). The UC Card could include the links about the jira tickets = ERD = implementation. Like the use case, if a ERD related to a UC requires a more elaborated explanation, then a document/diagram (sequence, class diagrams) will be created to present the solution, its implementation

hbraun	[11:17 AM]  
is this what you had in mind also?

cmoulliard	[11:19 AM]  
https://mojo.redhat.com/docs/DOC-141459 = A trello board with cards that we can move between different lists where a list = team or release or sprint or ...

hbraun	[11:20 AM]  
what about the contents/properties: Status, Prio, etc

[11:20]  
Should your ERD have the same contents? (edited)

cmoulliard	[11:20 AM]  
Custom fields can be defined for each card including priority/status/% of completeness ....

hbraun	[11:21 AM]  
yes, i am not talking about the tool is capable of. I trying to see if we mean the same thing when we say ERD

cmoulliard	[11:21 AM]  
yes. My ERD will have the same contents & properties.

hbraun	[11:21 AM]  
ok, good

[11:21]  
+1

[11:22]  
i think this needs to be explained to the engineers. not everybody is familiar with these processes

[11:23]  
what are your thoughts on regular risk assessment and management of those risks?

cmoulliard	[11:23 AM]  
From a PM perspective, we have tasks to deal with, assign them to members(s), track, calculate the workload, time estimated to release it and measure the risk. ERD, PRD are the areifacts that I must manage

[11:23]  
artefacts.

[11:24]  
I will develop what we have discussed here within a document or code-of-conduct and discuss it with Jiri/Bruno before to introduce the methodology with the teams

hbraun	[11:26 AM]  
+1

[11:26]  
flowcharts might be useful to depict the overall process

[11:27]  
i might be able to help with these

[11:27]  
but in general I think what you envision sounds reasonable

[11:27]  
the big remaining question is how we approach planning

[11:27]  
i.e. schedules, versions, etc

[11:28]  
i think the upfront planning doesn't work well at the moment

[11:28]  
so maybe establishing a product owner (scrum sense) and a prioritized backlog is more useful to manage the delivery

cmoulliard	[11:29 AM]  
sounds reasonable => rocks ...

hbraun	[11:29 AM]  
and work with time boxes, rather then requirements per version

cmoulliard	[11:29 AM]  
We will have a scrum master and I will recommend that you play this role for Swarm. YES ?

hbraun	[11:29 AM]  
so we can deliver value iteratively

[11:30]  
i.e. on a 8 week cycle

[11:30]  
oh, that’s an honor and a burden :slightly_smiling_face:

[11:30]  
but yes, count me in if the others agree

cmoulliard	[11:36 AM]  
I prefer that you do this job instead of Bob.

hbraun	[11:37 AM]  
Bob doesn’t like engineering processes anyway. But did you talk to him already?

cmoulliard	[11:37 AM]  
What do you mean by time boxes instead of requirements ?

[11:38]  
Not yet talked about that with Bob

hbraun	[11:38 AM]  
timeboxed=deliver what’s ready at the end of an iteration. requirements driven=work until all agreed upon req’s have been implemented

[11:40]  
i guess “fixed scope” is the alternative to “time boxed”. that’s a better term

[11:40]  
it seems our current approach to the PRD assumes “fixed scope” for 1.0

[11:41]  
i’d rather switch to “time boxed” to relief the pressure of having to deliver PRD _before_ anyone can pick up work

[11:41]  
i.e. it’s not helpful to discuss what should be delivered by summit next year

[11:42]  
we deliver what’s ready and useful at that point

cmoulliard	[11:42 AM]  
The delivery will be a mix of fixed & time boxed certainly ;-)

hbraun	[11:42 AM]  
but in between now and summit smaller iterations would be useful

[11:42]  
