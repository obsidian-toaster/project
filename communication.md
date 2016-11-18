# Communication

This section will detail how to proceed to communicate between the members of the project concerning the topics which are highlighted hereafter:

### Question/Ping

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

### Discussion

When a point, which have been started as a question, will require that:

- Multiple participants are involved to provide their advise in order to answer to the question or
- Somebody investigates and makes some research

then it makes more sense in this case to open a ticket on the github project : https://github.com/obsidian-toaster/platform

As the discussion could become an idea, a new user story or a task to be implemented, acting as such will allow to keep track of the request, assign it to a resource, manage the 
code changed using a Pull Request and finally adding the change to a milestone and sprint.

### Announce

The Obsidian Engineers/PM Mailing List should be used to communicate the agenda, minutes of the bi-weekly meeting, to publish general announces or changes but never to start a discussion
. This channel could also be used to prepare the sprint or communicate the project milestones. 

When an email about a meeting is published on the Obsidian Mailing List and that you want to participate or to invite somebody, please use this procedure :
@AI: I would like to ask you to nominate yourself for the call and forward this email to anyone you know should be aware. We will invite them and add them to the obsidian-pm-list as well.

### JIRA

Utility info about the JIRA Obsidian Toaster project

```
ID: OBST
Name: Obsidian Toaster
Lead: Jiri Pallich / jpallich@redhat.com
Admin: Charles Moulliard / cmoullia@redhat.com , Jay Balunas / jbalunas@redhat.com , Rodney Russ / rruss@redhat.com , Bruno Georges / bgeorges@redhat.com , Jiri Pallich / jpallich@redhat.com

Starting schema: JBEAP without CDW (all issue types, agile enabled)
```

### Trello

#### Info 

You can find more info about how to use Trello as presented by OpenShift Team

- https://trello.com/b/22FjgidH/how-we-use-trello
- https://trello.com/c/FmXGaXIj/56-getting-started-how-we-use-trello

The Trello boards will be used to manage the tasks related to a project. The "generator by example" which corresponds to a deliverable of obsidian can be assimilated to a project like vert.x, swarm, EAP, etc.
The board which is a kanban view will help us to figure out what should be tracked, included into a sprint or not, discussed, reviewed.... It could be possible that some tasks will not been linked to a JIRA or Github issue 
as they correspond to a request to create a document, contact a group, team, configure a machine, ... or could be used to translate a user story to ERD response which contains sometimes link(s) to jira/bugzilla/...
(example : https://trello.com/b/wqe9UaaZ/developer-experience)

#### How to create a card

A trello card can be created from GMail at the condition that you have installed the Chrome extension ("https://chrome.google.com/webstore/detail/gmail-to-trello/oceoildfbiaeclndnjknjpfaoofeekgl").
When you will create from an email a card, you can select the board and the list where the card should be created.
 
When a Trello card is created, please add it to the list "New" in order to allow the members part of the board to review it.
When they will run their weekly call, the "new" listed cards will be reviewed, accepted or refused and assigned to member(s) including also the definition of a due date. 
The dates defined for the cards will allow us using the power-ups "calendar" app to define sprints like also to review the tasks assigned during the weekly call.
 
### Meeting minutes

The template to be used to generate the minutes of a meeting is available hereafter. An example about such minutes is posted here : https://docs.google.com/document/d/1SJJod6qi5i1_w50BwR98H6RIN2X_qK81wf0_ts63wfg

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

 
 



