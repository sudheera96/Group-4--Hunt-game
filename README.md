# Group-4--Hunt-game
## Statment of Purpose
2020 has turned out to be an interesting year. We would like to create an outside, socially-distant game that:

1. Encourages outside activity.
2. Introduces Bearcats to unique and special parts of campus.
3. Supports teamwork, while allowing players to remain safe.
4. Could be an engaging icebreaker for various student organizations.
## Overview
Hunt game is the very responsive game app which can be played on any device like phone (IPhone and Android), laptop, Ipod. This game completely is an outside activity where people can have the opportunity to visit all the locations of their respective universities by solving quests. Hunt games makes people to do many tasks through different functionalities in order to engage in icebreaker. The functionalities like user can act like team player, designer of quest, hunt master, competition creator, and creator of quest location within 10 * 10 from his/her location, quest creator with specified time limits for other players to solve. Also player can invite other players, reject invitation from other players.About rejection of invitation, hunt game have the shared responsibility like if the user won’t accept the invitation from other user, hunt game itself reject the requests after certain period of time. Points can be achieved by the user depends upon the player reaching the location, player completing the quest, difficulty level of game, time taken to complete the game. Security can also be addressed for throughout the hunt game app as the data request and responses were end to end encrypted. This app also provides the visible and audible feedback to the users.Overall theme of the app can also be customized depending on the usage of app in different schools.This app justifies engaging activity between the users in pandemic situations.


## Benefits
1.	Interact with friends
2.	Meet new people
3.	Improve creative skills
4.	Learn leadership skills
5.	Detail exploration of the university and its services
6.	Gain knowledge on college history
7.	Improve problem solving skills
8.	Learn Managing skills
9.	Play on any device
10.	Keeps you motivated and Won’t feel alone
11.	Acts like a workout
12.	Free marketing for University as users share across social media

## Cons

1. User must register into game with email ID. Until user won't register he/she are uneligible to play the game.
2. Even for creating the competiton and for creaing quest user need to register in the game.

## Client
* Dr. Denise Case

Dr. Denise Case is the Assistant Professor of Computer Science, Northwest Missouri State University.

## Administrator Roles in Application

* [Access to all information including app settings](https://github.com/sudheera96/Group-4--Hunt-game/issues/2)

## User Roles in Application
* Any user may choose to:
   1. Create and manage a team (serve as captain)
   2. Create and manage a quest (serve as quest creator)
   3. Launch a competition (serve as hunt master)
   4. Join a team and participate in a quest (serve as a player)
   
* Any user can choose to create a team.

   1. The user serves as captain of any team they create.
   2. The captain provides a team name.
   3. The captain provides a list of emails of invited members.
   4. A user can accept the team invite and become a team player or reject it.
   5. After three days, if not accepted, assume rejection.
   6. Invite will be in the form of email to the registered email while creating an account.
   
* Any user can choose to design a quest, but will not be able to create a new location.

   1. The user serves as designer of any quest they create.
   2. The designer provides a quest name.
   3. The designer provides a list of locations for the quest.
   4. Admin is the designer of locations.
   4. For each location, the designer provides a location number.
   5. For each location, the designer provides location coordinates (either by entering numbers OR based on a 10' x 10' square around their current location)
   
 * Any user can choose to launch a competion.

   1. The user serves as the hunt master of the competion.
   2. The hunt master specifies the start date and time for the competion.
   3. The hunt master specifies the end date and time for the competion.
   4. The hunt master chooses an existing quest for the competion.
   5. The hunt master invites a list of teams to compete about a week before.
   
   
   6. Each team captain can accept or reject the invitation.
   7. By 24 hours before the competition, if not accepted, assume rejection.
   8. Only the User with admin previlages will be allowed to add new locations.
* Other Important Roles.
   1. Developer team roles are not the same as user roles.
   2. The user will be able to create competition, add locations, and create Quests. 
   3. The developer will have complete rights on the application.
   4. The user who creates the quest or competition or location will not be able to play as a player.
   


## List of User Roles
* Full Stack Developer - Krishna Sumanth ( Team lead)
* Project Manager -  Swaroop Reddy
* Full Stack Developer - Yashwanth Damera
* UI Developer - Prasad 
* Database Engineer - Sri Sudheera Chitipolu
* FrontEnd Developer and Testing - Sai Krishna

## Entity Relation Diagram
![ER Diagram](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/Group%20-%204%20Proposal%20ER.jpeg?raw=true)

* In this project we will be handling with data of different aspects.
Most Important data here is the user entity. User is the minimum requirement for a person to any role like to be a player, be in a team, participate in a competition and play a quest.
* We have associative entities in places where relation of multiple degree between entities - Player & Team, Competition & Team, Location & Quest to avoid multiple values which may result in hindering with the Primary Keys

## Sample Data Handling

For Instance, we have 20 users who will be able to login with their unique emfor our app and 2 users have created two different quests named 'Dragon Hunt' and 'Duck Hunt'. Now, we have picked 11 locations in University to use as the checkpoints for these quests.

There is a competition with ID CI4011 in which 19 players have formed into 4 teams with 5 members in three teams and 4 members in one team. Two quests have used 4 locations each to form a hunt and based on the time taken by the teams, the teams have been scored accordingly.

We have tested a simulation using sample data. We introduced only one competition which can access two quests created by two users which are madeup using the locations identified. We thought of introducing points system to the location so that points can be issued to teams based on the locations covered instead of other parameters.

We issue a final team score to each team and then we compare scores and finalize a winner.

### User entity with sample data

| S.No | E-mail                         | Password        | Username          | Date created | Date last accessed |
|------|--------------------------------|-----------------|-------------------|--------------|--------------------|
| 1    | alex154590@gmail.com           | ***********     | Alekya_Jaddu      | 8/3/2020     | 8/14/2020          |
| 2    | samarpita.chandolu@outlook.com | *********       | Annie_Chandolu    | 6/3/2020     | 8/15/2020          |
| 3    | bhanu1994@gmail.com            | ************    | Bhanu_Prakash     | 7/22/2020    | 8/14/2020          |
| 4    | chandu131198@gmail.com         | *************** | Chandana_Priya    | 8/17/2020    | 8/16/2020          |
| 5    | chanduhvg@gmail.com            | ************    | Gopi_chand        | 8/16/2020    | 8/15/2020          |
| 6    | p.harichandraprasad@gmail.com  | *********       | Hari_Chandra      | 8/16/2020    | 8/14/2020          |
| 7    | krishna.ksk1996@gmail.com      | **********      | Krishna_Sumanth   | 7/11/2020    | 8/16/2020          |
| 8    | mohansai03@outlook.com         | ***********     | Mohan_Sai         | 7/30/2020    | 8/14/2020          |
| 9    | prasad.gd@gmail.com            | **********      | Prasad_GD         | 7/9/2020     | 8/14/2020          |
| 10   | pruthvunaskanti@hotmail.com    | *********       | Pruthvi_Naskanti  | 5/13/2020    | 8/14/2020          |
| 11   | raviteja.pagidoju@gmail.com    | *************   | Ravi_Teja         | 8/1/2020     | 8/15/2020          |
| 12   | saikrish1545@gmail.com         | **************  | Sai_Krishna       | 8/8/2020     | 8/16/2020          |
| 13   | teja2004@woutlook.com          | ***********     | Sai_Teja          | 8/4/2020     | 8/14/2020          |
| 14   | srkvodnala@gmail.com           | ************    | Shiva_Ramakrishna | 7/3/2020     | 8/16/2020          |
| 15   | csrisudheera@gmail.com   | *************   | Sri_Sudheera      | 6/19/2020    | 8/16/2020          |
| 16   | swaroopreddy.g@gmail.com       | ************    | Swaroop_Reddy     | 5/31/2020    | 8/16/2020          |
| 17   | swaroopat@hotmail.com          | ************    | Swaroopa_Reddy    | 5/5/2020     | 8/14/2020          |
| 18   | kiran021997@gmail.com          | ***********     | Usha_Kiran        | 6/6/2020     | 8/15/2020          |
| 19   | yashwanthrocks@gmail.com       | **********      | Venkata_Yashwanth | 3/6/2020     | 8/16/2020          |
| 20   | vishal041197@outlook.com       | ***********     | Vishal_Reddy      | 12/5/2020    | 8/15/2020          |

### Player enity with sample data

| S.No | PlayerID | Player NickName |
|------|----------|-----------------|
| 1    | 12010    | Jack            |
| 2    | 12011    | Loser           |
| 3    | 12012    | Joy             |
| 4    | 12013    | Charles         |
| 5    | 12014    | Shooter         |
| 6    | 12015    | Hunter          |
| 7    | 12016    | Krish           |
| 8    | 12017    | Anna            |
| 9    | 12018    | GD              |
| 10   | 12019    | Yash            |
| 11   | 12020    | Gopi            |
| 12   | 12021    | Alex            |
| 13   | 12022    | Chainbreaker    |
| 14   | 12023    | Kingkong        |
| 15   | 12024    | Godzilla        |
| 16   | 12025    | Hulk            |
| 17   | 12026    | Batman          |
| 18   | 12027    | Deadpool        |
| 19   | 12028    | Chainsmoker     |

### Team entity with sample data

| S.No | TeamID | Team Name          | Creator              | Date Created | Date last Edited |
|------|--------|--------------------|----------------------|--------------|------------------|
| 1    | 101    | Thunder Guys       | Prasad_GD            | 8/20/2020    | 8/24/2020        |
| 2    | 102    | Mavericks          | Swaroop_Reddy        | 8/19/2020    | 8/20/2020        |
| 3    | 103    | Sunrisers horizons | Shiva_Ramakrishna    | 8/22/2020    | 8/23/2020        |
| 4    | 104    | Barbies            | Chandana_Priya       | 08/19/2020   | 8/23/2020        |
| 5	 | 105 	 | Hunters	          |Gopichand_Bandarupalli| 08/30/2020	| 8/31/2020        |


### Location entity with sample data

| S.No | Location Number | Location Clue                            | Location Coordinates   |
|------|-----------------|------------------------------------------|------------------------|
| 1    | L90121          | Tall tower which resonates               | 40.3520° N, 94.8825° W |
| 2    | L90122          | Two persons found studying but not alive | 42.3620° N, 89.7732° W |
| 3    | L90123          | Place with lot of shelves                | 39.7587° N, 91.2457° W |
| 4    | L90124          | Place where it continuously showers      | 41.7658° N, 92.0972° W |
| 5    | L90125          | large ellipse                            | 40.4397° N, 91.8572° W |
| 6    | L90126          | breaks a lot of sweat                    | 42.1258° N, 91.0976° W |
| 7    | L90127          | Represents every nation                  | 42.2152° N, 91.9231° W |
| 8    | L90128          | place with lot of computers              | 41.8787° N, 93.9056° W |
| 9    | L90129          | chicken…chicken                          | 42.3620° N, 89.7732° W |
| 10   | L90130          | coffee spot                              | 40.6799° N, 90.8925° W |
| 11   | L90131          | fun and frustration                      | 42.1258° N, 91.0976° W |

### Quest entity with sample data

| S.No | QuestID | QuestName   | Designer        | Date Created | Date last Accessed |
|------|---------|-------------|-----------------|--------------|--------------------|
| 1    | 10011   | Dragon Hunt | Swaroop_Reddy   | 8/23/2020    | 8/24/2020          |
| 2    | 10022   | Duck Hunt   | Krishna_Sumanth | 8/24/2020    | 8/24/2020          |

### Competition entity with sample data

| S.No | CompetitionID | Competition Name | Creator | Date Created | Start     | End       |
|------|---------------|------------------|---------|--------------|-----------|-----------|
| 1    | CI4011        | Dragon Duck      | Krishna | 8/23/2020    | 8/24/2020 | 8/31/2020 |

### TeamPlayer Mapping entity with sample data

| S.No | TeamID | PlayerID | Date Invited | Join Status |
|------|--------|----------|--------------|-------------|
| 1    | 101    | 12010    | 8/23/2020    | Y           |
| 2    | 103    | 12011    | 8/23/2020    | Y           |
| 3    | 102    | 12012    | 8/23/2020    | Y           |
| 4    | 103    | 12013    | 8/23/2020    | Y           |
| 5    | 101    | 12014    | 8/23/2020    | Y           |
| 6    | 104    | 12015    | 8/23/2020    | Y           |
| 7    | 102    | 12016    | 8/23/2020    | Y           |
| 8    | 104    | 12017    | 8/23/2020    | Y           |
| 9    | 103    | 12018    | 8/23/2020    | Y           |
| 10   | 101    | 12019    | 8/23/2020    | Y           |
| 11   | 104    | 12020    | 8/24/2020    | Y           |
| 12   | 102    | 12021    | 8/24/2020    | Y           |
| 13   | 104    | 12022    | 8/24/2020    | Y           |
| 14   | 101    | 12023    | 8/24/2020    | Y           |
| 15   | 102    | 12024    | 8/24/2020    | Y           |
| 16   | 103    | 12025    | 8/24/2020    | Y           |
| 17   | 101    | 12026    | 8/24/2020    | Y           |
| 18   | 103    | 12027    | 8/24/2020    | Y           |
| 19   | 102    | 12028    | 8/24/2020    | Y           |
|20	 | 105	 | 12029	   | 8/30/2020	   | Y           |
|21	 | 105	 | 12014	   | 8/30/2020	   | Y           |
|22	 | 105	 | 12015	   | 8/30/2020	   | Y           |
|23	 | 105	 | 12016	   | 8/30/2020	   | Y           |
|24	 | 105	 | 12017	   | 8/30/2020	   | Y           |

### QuestLocation Mapping entity with sample data

| S.No | QuestID | LocationID |
|------|---------|------------|
| 1    | 1       | L90121     |
| 2    | 1       | L90122     |
| 3    | 2       | L90123     |
| 4    | 2       | L90124     |
| 5    | 1       | L90125     |
| 6    | 2       | L90126     |
| 7    | 1       | L90127     |
| 8    | 2       | L90128     |
| 9    | 1       | L90129     |

### Competition Mapping entity with sample data

| S.No | CompetitionID | TeamID | Team Score |
|------|---------------|--------|------------|
| 1    | CI4011        | 101    | 445        |
| 2    | CI4011        | 102    | 1220       |
| 3    | CI4011        | 103    | 3031       |
| 4    | CI4011        | 104    | 2805       |
| 5    | CI4011        | 105    | 2806       |


## Link to Microsoft Excel file containg sample data for all entities 
[Spreadsheet with sample data](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/GDP_SampleData.xlsx?raw=true)

## Link to Project
[PROJECT LINK](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/README.md)

## Hosted Link
[Hosted Link](https://sudheera96.github.io/Group-4--Hunt-game/)

## User Interface Design:<br>

* User Login to the Web Application:<br><br>

![Login Page](https://raw.githubusercontent.com/sudheera96/Group-4--Hunt-game/master/folder/loginpage.png)
<br>
* The following page will be displayed once the user logs into the web appliction.
* The user will be able to select Team, Quest, Compition and profile.<br><br>

![2nd Page](https://raw.githubusercontent.com/sudheera96/Group-4--Hunt-game/master/folder/2nd%20.png)
<br>
* Once the user selects Team Icon.
* The below page will be displayed, where the user will be able to create a team.
* The user who creates the team will server as a captain of the team and will be able to send invite to the other user he wishes to add. <br>
![team page](https://raw.githubusercontent.com/sudheera96/Group-4--Hunt-game/master/folder/teampage.png) <br>

* Once the invite is sent.
* If other users accepts the request, they will be added into the user team.
* For the user who wish to create the quest, the user will have to select Quest Icon.
* After selecting the Quest Icon, the user will be able to view the existing Quests.
* The user will be able to selct the existing Quest or wish to select Creat New Quest. <br>
![Quest Page](https://raw.githubusercontent.com/sudheera96/Group-4--Hunt-game/master/folder/Questpage1.png) <br>
* After clicking the views of respective quest,Then it  will be able to view the details of the existing quest. <br>
![existing page](https://raw.githubusercontent.com/sudheera96/Group-4--Hunt-game/master/folder/Quest2.png) <br>
* If the user selects Crete New Quest, The user will be able to add a set of locations and create a new quest
* Only Admin will be able to add the locations.
* The user should enter quest name, loaction name, location ID, location, location coordinates and Clues. <br>
![Add location](https://raw.githubusercontent.com/sudheera96/Group-4--Hunt-game/master/folder/addlocartioninquest.png) <br>
* The user who wish to join a Competition will have to click the Competition Icon and select the Existing Competitions.
* If the user wants to create a new compition, the user should click create new competition button. <br>


![competition](https://raw.githubusercontent.com/sudheera96/Group-4--Hunt-game/master/folder/Comprtionnext.png) <br>
* When the user clicks on the existing competitions, then he will be able to join or leave the competition.
* Once the user selects the create new competition, the user will be directed to the Quest page and continue as listed in the above. <br>
![game](https://raw.githubusercontent.com/sudheera96/Group-4--Hunt-game/master/folder/gameUI.png) <br>
* When the user clicks on the competition, Quests will be displayed. when clicked on the Quests, maps will open with the clue in the bottom. <br>



## JIRA Link to Project
[JIRA LINK](https://group-4-hunt-game.atlassian.net/secure/RapidBoard.jspa?rapidView=1)

### JIRA Sprint 1

![JIRA SPRINT 1](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/folder/Sprint1.png?raw=true)

#### User Story 1

As a User, a player can register to Hunt Game application with valid email address.

#### Acceptance Criteria

- User should have valid email ID 

#### User Story 2

As a User, the verification is successful then and user create a password

#### Acceptance Criteria

User should able to verify the mail sent to his/her mail ID.

#### User Story 3

As a User, after creating the password user should log in successfully 

#### Acceptance Criteria

User can able to change password after first log in.

#### User Story 4

As a user, schedule management planned for this game hunt application

#### Acceptance Criteria

Team manager should be able to schedule meetings and check whether work is going according to plan or not

#### User Story 5

As a user, risk analysis should be estimated

#### Acceptance Criteria

As a team, we have estimate the risk for creating this app. for example Market risk, User mobile location access

#### User story 6

As a User, admin will have all application settings

#### Acceptance Criteria

If user has admin access he can creat edit delet the quests,teams,locations and users in the application

### JIRA Sprint 2

![JIRA SPRINT 2](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/folder/Sprint2.png?raw=true)

#### User story 1

As a user, a player can create team and serve as captain 

#### Acceptance Criteria

User can create a team and invite the players to join team or can accept invitation who reqested to join in team

#### User story 2

As a user, a player can request to join in multiple teams and should be accepted by team captain

#### Acceptance Criteria

A player can request to join in multiple teams

#### User story 3

As a user, if a team joins in the quest every user should get notification before starting of quest

#### Acceptance Criteria

User should get notificaton before the quest start time to alert the user

#### User Story 4

As a User, the player can have location coordinates along with clues  

#### Acceptance Criteria

When the quest started, if the user is participating in the quest he/she can have location coordinates along with clues

#### User Story 5

As a User, a player can create quest or participate in hunt game

#### Acceptance Criteria

A user can create a quest game or he can be participate as player but cannot do both.

#### User Story 6

As a User, a player can have limit time to crack the clue 

#### Acceptance Criteria

User who is participating in the quest will have limit time crack the quest

### JIRA Sprint 3

![JIRA SPRINT 3](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/folder/Sprint3.png?raw=true)

#### User Story 1

As a team, we have to work on UI implementation 

#### Acceptance Criteria

UI Team should take the task and complete the UI implementation

#### User Story 2

As a team, we have to work on infrastructure Management

#### Acceptance Criteria

Infrastructure Management team will take the task for the Security updates, patches, 24/7 monitoring

#### User Story 3

As a team, we have to work on Back end Implementation

#### Acceptance Criteria

Back end team will be using Node JS to complete the task.

#### User Task 4 

As a team, we have to do UI development and testing

#### Acceptance Criteria

After the development of UI, testing will be testing each and every page.

#### User Task 5

As a team, we have to do database architecture and management

#### Acceptance Criteria

Database architecture team will design, development, implementation ofcomputer programs that store organize information

#### User Task 6

As a team, we have to do Back end Development and Testing

#### Acceptance Criteria

After the back end development, testing should be done using selenium with java.


## Technology stack descriptions
 * HTML: 
   Hypertext Markup Language (HTML) is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading    Style Sheets (CSS) and scripting languages such as JavaScript.
   
 * CSS:
   CSS stands for Cascading Style Sheets. CSS describes how HTML elements are to be displayed on screen, paper, or in other media. CSS saves a lot of work. It can control the      layout of multiple web pages all at once. External stylesheets are stored in CSS files.
   
 * Java Script:
   JavaScript is a text-based programming language used both on the client-side and server-side that allows you to make web pages interactive. Where HTML and CSS are languages      that give structure and style to web pages, JavaScript gives web pages interactive elements that engage a user.
   
 * Node-JS
   Node. js is a platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. Node. js uses an event-driven, non-blocking I/O model    that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.
 
 * Git-Hub
   GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also      provides access control and several collaboration features, such as a wikis and basic task management tools for every project.Also, through git we can keep track of the flow    of work like who commited what. Other good feature of the git is to we can select any template for host page.
   
 * Mongo DB
   MongoDB is a document-oriented NoSQL database used for high volume data storage. Instead of using tables and rows as in the traditional relational databases, MongoDB makes      use of collections and documents.
   
 * VS Code:
   It is widely popular among web development comunity, as it is open source and license free tool. It supports almost any file we throw at it.
   
 * Markdown:
   Most accessible simple format webpage to build most versatile documentation.
   
  ## Schedule Management
 
  [Link for Schedule Management](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/ScheduleMangement.xlsx)
  
  ![Schedule Management](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/folder/Schedulemanagement.JPG)
  
   
  ## Cost Estimate
  [link for Cost Estimate](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/CostEstimate.xlsx)
  
  ![Cost Estimate](https://github.com/sudheera96/Group-4--Hunt-game/blob/master/newcost.png?raw=true)

 
  # Electronic Form RFP (Request For Proposal)
  [RFP- Hunt Game](https://github.com/denisecase/rfp-hunt/blob/master/rfp-hunt.md)
  
  

