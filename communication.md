# Communication

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

 
 



