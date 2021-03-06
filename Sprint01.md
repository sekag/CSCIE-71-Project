# Sprint 1 (11/06-11/17)

## Forecast

We forecasted we could get **5 story points** done during this sprint. Our forecast is on conservative side primarily based on team member skill mix and technical demands of the actual prioritized PBIs. As this is the first sprint for the Brain Cradle Team, we were not sure what our actual velocity would be. Regardless, the forecast accounted for the fact that we each would need to locally configure the project, work through the learning curve of new frameworks, and be able to iterate on our localhost before we were able to begin work on the stories that actually delivered product value. 
The forecast correlated to the first story from our [Initial Ordered Product Backlog](https://trello.com/b/qb2G2V5r/product-back-log):

| __Number__ | __Title__ | __Story Points__ | __Summary__
| --- | --- | --- | --- |
| 1. | Site Navigation | 5 pts | Andrew Kiriakedes (Andy) would like to be able to click on links at the top of the website that are consistent across pages, clearly outline where each link will send him, and ensures that he's only ever one click away from each of the sites primary features. |


## Actual

We had few hiccups, but were able to close on the selected user story forecasted within the sprint (reference our [Definition of Done](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/README.md)). 

We deployed the user story in production at following URL:

[Site Nav](https://braincradleai.firebaseapp.com)

### Acceptance Criteria and Sprint Task 

(reference our [Sprint Task & Acceptance Criteria](https://trello.com/c/4e62yBqy/10-site-navigation)). 

## Burndown

Our burndown chart, shown below, is based on the completion of each user story [Refer to User Story in Trello](https://trello.com/c/4e62yBqy/10-site-navigation) which were decomposed from the PBIs committed to the sprint. 

![Burndown Data for Sprint 1](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/sprint1_burndown_excel.png)

![Burndown Chart Sprint 1](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/sprint1_burndown.png)

## Daily Scrums (2-day sample)

### Sunday, November 12th

#### Devon
_What did you accomplish yesterday?_
> setup local environment

_What will you do today?_
> download the shell code and dev framework 

_What obstacles are impeding your progress?_
> none

#### Shivas
_What did you accomplish yesterday?_
> I created a  basic code framework and local environment along with instructions for the team to replicate on their local.

_What will you do today?_
> Explore firebase hosting

_What obstacles are impeding your progress?_
> none

#### Ailing
_What did you accomplish yesterday?_
> Setup local environment

_What will you do today?_
> Research BDD with angular

_What obstacles are impeding your progress?_
> No past experience on angular framework. 

### Tuesday, November 14th

#### Devon
_What did you accomplish yesterday?_
> downloaded the basic shell and worked on front end css

_What will you do today?_
> expand on the front end code to build basic navigation 

_What obstacles are impeding your progress?_
> none

#### Shivas
_What did you accomplish yesterday?_
>  I deployed the shell app on firebase hosting server.

_What will you do today?_
> Working on unit test cases for the app

_What obstacles are impeding your progress?_
> Limited knowledge on Unit Test integration with angular

#### Ailing
_What did you accomplish yesterday?_
> Identified and integrated BDD framework with angular using selenium

_What will you do today?_
> Create BDD test suite

_What obstacles are impeding your progress?_
> No past experience on angular framework. Help in form of reference articles are being provided.


### Impediments

_IRP = Impediment Removal Plan_

#### Digant - Nov 12th, 06:35 pm
> Not sure how to setup development framework?

IRP: Shivas provided instructions on slack to download base development framework and setup on WebStorm.

#### Devon - Nov 12th, 07:46 pm
> Where do I put the img/video folders in Angular? Do the go under each component sub-folder such as “blog” as if I were making mini websites?

IRP: you can put it under resources

#### Ailing - Nov 12th, 07:52 pm
> recommendations on tools for unit test and BDD with angular

IRP: Link provided on slack (https://docs.angularjs.org/guide/unit-testing)

## Collaboration
Our Team met as a group at least 2x per week to synchronize and elevate obstacles along our critical path; additionally, individuals teamed up to pair program in order to solve various engineering tasks.  

| __Date__ | __Meeting Type__ |
| --- | --- |
| 12 NOV | Standing Team Meeting |
| 14 NOV | Daily Scrum |
| 15 NOV | Standing Team Meeting |
| 19 NOV | Sprint Review & Retrospective |

1. Example of a peer code review (part of our [Definition of Done](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/README.md))

 ![Code Review](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/mob-program1.png)

2. Example of a mob programming  (part of our [Definition of Done](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/README.md))

 ![Mob Programming](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/mob-program3.png)

3. Example of a standing team meeting
 
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/team-collab1.png)
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/team-collab2.png)
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/team-collab3.png)
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/team-collab4.png)



### Behavior-Driven Development & Unit Tests

We used the [cucumber](https://cucumber.io/) framework and  [selenium](http://www.seleniumhq.org/) to run our Behavior-Driven Development (BDD) tests. Specifically we tested site navigation using BDD. See the screenshots below (showing test failed and then passed). 

![BDD Fail Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/BDD_Fail_Case.png)
   
 ![BDD Pass Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/BDD.png)
 
 BDD source code is checked here: https://github.com/BrainCradle/BrainCradle/tree/master/BDD/BrainCradleTest
   
Our TDD and unit tests (we have used tool called Karma) are shown below including a failed one and passed ones.

![TDD fail](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/TDD_Fail.png)

 ![unit cases passed](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/TestCases_Passed.png)
 
 ![refer ot screenshot](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/UnitTests.png)
 
![unit tests](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/UnitTests2.png)
 
![unit tests](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/UnitTests3.png)

The unit test cases are checked here: https://github.com/BrainCradle/BrainCradle/tree/master/braincradleapp/tests

## Sprint Review and Retrospective

We conducted our sprint review with stakeholders and Scrum Team retrospective on NOV 19TH. 

### Sprint Review Stakeholder Feeback

We reviewed the sprint 1 user story in production [Site Nav](https://braincradleai.firebaseapp.com) with our primary stakeholder, Andy.
![Andy Call Log](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Andy_Review_Call.png)
Andy is pleased with the progress of our efforts. He offered the following feedback, mostly looking towards the next sprint:

- Overall looks clean. Clearly labeled. Font is readable. 
- Loves the responsiveness. Woo Firebase! 
- Tab highlighting should be added as it doesn't show current tab.
- Dual menu is confusing. Maybe have a standard top bar nav and left hand nav
- Selecting the proper categories under the "Examples Tab" is extremely important. Prefer's the label "Examples" over "Solutions".
- Prefers the term "Real-world Applications" to  "Applications".

This feedback will be absorbed into the product backlog (and groomed) ahead of sprint 2 planning.
 
### Scrum Team Retrospective

While the retrospective is a generally closed door event, we chose to share these highlights:

- Angular, Karma & Firebase frameworks had an initial steep learning curve. More pinpointed documentation for features would really help in next sprint. Also framework experts should spend some time walking through the nuances of the code and best practices.
- Despite not being local - the team has managed to leverage tools like slack, google hangouts, conference calls, Trello etc. to collaborate virtually and make progress on the sprint. 
- However there is still no substitute to being able to work face to face in person and it took a while for the team to get comfortable and streamline commmunications. We should look for an opportunity to work together on a future sprint in person if circumstances and calendars permit.
