Project 3 Demo video: https://youtu.be/V9sb925ljWE

<p align="center"><img src="https://github.com/shikhanair/TeachersPetBot/blob/main/images/teacherspet.png" alt="alt text" width=200 height=200>
  
  <h1 align="center"> Teacher's Pet </h1>
  
<h2 align="center"> Streamline Your Class Discord</h2>

[![Build Status](https://app.travis-ci.com/qchen59/TeachersPetBot.svg?branch=main)](https://app.travis-ci.com/github/qchen59/TeachersPetBot)
[![Coverage Status](https://coveralls.io/repos/github/qchen59/TeachersPetBot/badge.svg?branch=main)](https://coveralls.io/github/qchen59/TeachersPetBot?branch=main)
[![DOI](https://zenodo.org/badge/427178638.svg)](https://zenodo.org/badge/latestdoi/427178638)
![Python](https://img.shields.io/badge/python-v3.7+-brightgreen.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![GitHub](https://img.shields.io/github/license/qchen59/TeachersPetBot)
[![GitHub issues](https://img.shields.io/github/issues/qchen59/TeachersPetBot)](https://github.com/qchen59/TeachersPetBot/issues)
![GitHub closed issues](https://img.shields.io/github/issues-closed/qchen59/TeachersPetBot)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/qchen59/TeachersPetBot?include_prereleases)](https://github.com/qchen59/TeachersPetBot/releases)
[![GitHub all releases](https://img.shields.io/github/downloads/qchen59/TeachersPetBot/total)](https://github.com/qchen59/TeachersPetBot/releases)
[![Platform](https://img.shields.io/badge/platform-discord-blue)](https://discord.com/)
![Lines of code](https://img.shields.io/tokei/lines/github/qchen59/TeachersPetBot)


  Click Below to Watch Our Video!
[![Watch the video](https://github.com/shikhanair/TeachersPetBot/blob/main/images/teacherspetbot.png)](https://youtu.be/tExF88LHqgE)
  
  

Software Engineering Project 3 for CSC 510

Teacher's Pet is a Discord Bot for class instructors to streamline their Discord servers. Discord is a great tool for communication and its functionalities can be enhanced by bots and integrations. There are many tools for organizing classes, but they are often hard to manage. They rarely have good communication mechanisms or ability to connect with other tools. This bot allows instructors to host their classes on Discord, combining communication tools with functionality for assignments, scheduling, and office hours. Instructors and students no longer have to go between platforms to view course details, forums, events, calls, and more.

<h2 align="center"> Bot Commands </h2>

:open_file_folder: [!setInstructor](https://github.com/qchen59/TeachersPetBot/blob/main/cogs/setInstructor.py) Set a server member to be an instructor (Instructor command)

:open_file_folder: [!ask](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/ask_and_answer.md)  Ask a question  

:open_file_folder: [!answer](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/ask_and_answer.md) Answer a question  

:open_file_folder: [!oh enter](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/oh.md) Enter an office hour queue as an individual student 

:open_file_folder: [!oh enter *Group ID*](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/oh.md) Enter an office hour queue with a group of students  

:open_file_folder: [!oh exit](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/oh.md) Exit the office hour queue  

:open_file_folder: [!oh next](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/oh.md) Go to next student in queue as an instructor (Instructor command)  

:open_file_folder: [!create](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/create.md) Start creating an event (Instructor command)  

-----

:open_file_folder: [!addhw](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/addhw.md) This command lets the user (either the TAs or professor) to add a homework as a reminder to the discord channel

:open_file_folder: [!changeduedate](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/changeduedate.md) This command lets the user update the due date.

:open_file_folder: [!clearreminders](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/clearreminders.md) This command lets the user delete all the reminders irrespective of courses or homeworks.

:open_file_folder: [!coursedue](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/coursedue.md) This command lets the user display all the homeworks that are due for a specific course.

:open_file_folder: [!deletereminder](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/deletereminder.md) This command lets the user delete a reminder for a specified coursename and homework.

:open_file_folder: [!duethisweek](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/duethisweek.md) This command lets the user display all the homeworks that are due this week for all the courses.

:open_file_folder: [!duetoday](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/duetoday.md) This command lets the user display all the homeworks that are due today for all the courses.

:open_file_folder: [!listreminders](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/listreminders.md) This command lets the user display all the homeworks that are due for all the courses.

:open_file_folder: [!notify](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/notifyme.md) This command lets the user display all the homeworks that are due this week for all the courses.

:open_file_folder: [!whois](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/member_information.md) This command lets the Instructors get information about the member using his/her username. 

:open_file_folder: [!multipoll](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/multipoll.md) This command lets the Instructors create a poll with specified number of choices ( 2 to 10 ).

:open_file_folder: [!poll](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/poll.md) This command lets the Instructors create a poll with 2 choices.

:open_file_folder: [!take](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/take.md) and :open_file_folder: [!eventcsv](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/take.md) The eventcsv command lets instructors get a example CSV of all the events in a course. You can download the csv and upload it back to the bot with the take command. This will let you add all the events to the calendar in one go. When using the take command, drag the csv to discord and use the take command in the comment as you upload it.

:open_file_folder: [!voice_channel](https://github.com/qchen59/TeachersPetBot/blob/main/docs/Command_Details/voice_channel.md) This command lets the Instructors create vocie channels.

<h2 align="center"> Installation and Running </h2>

#### Tools and Libraries Used
In addition to the packages from [requirements.txt](https://github.com/qchen59/TeachersPetBot/blob/main/requirements.txt) which need to be installed, please have the following installed on your machine:
* [Python 3.9.7](https://www.python.org/downloads/)
* [Sqlite](https://www.sqlite.org/download.html)

To install and run Teacher's Pet, follow instructions in the [Installation and Testing Guide](https://github.com/qchen59/TeachersPetBot/blob/main/Installation.md).

<h2 align="center"> Testing </h2>

To run tests on the Teacher's Pet, follow instructions in the [Installation and Testing Guide](https://github.com/qchen59/TeachersPetBot/blob/main/Installation.md).

<h2 align="center"> For Developer </h2>

#### API Documentation

To better help developers, the API documentation can be found here [API Documentation](https://htmlpreview.github.io/?https://github.com/qchen59/TeachersPetBot/blob/main/docs/TeachersPetBot/index.html)

<h2 align="center"> TeachersPetBot Features </h2>


### Initialization

When Teacher's Pet has been added to a new server as a bot, it will do the following:

* Create a new role called Instructor with Administrative permissions if one does not already exist
* Add the owner of the guild to the Instructor role
* Create a #q-and-a channel if one doesn't already exist
* Create a #course-calendar channel if one doesn't already exist
* Create 4 voice channels for one to one interaction with TAs 
* Create 40 voice channels (one for each group) with a limit of maximum 6 participants

In addition to this auto-set up, there is also a command which allows a user with the Instructor role to give the same role to another user. This command will only work for users with the Instructor role already (for example, the guild owner).

![alt text](https://github.com/shikhanair/TeachersPetBot/blob/main/images/bot_join.png)

### Q&A
The Q&A functionality allow students to ask and answer questions anonymously. The questions are numbered and when answers are sent, they are combined with the question so they can be easily found. Answers are also marked with `Student Ans` and `Instructor Ans` to distinguish between the sources.  
To ask a question, type `!ask "Question"` in the #q-and-a channel. Example: `!ask "When is the midterm?"`.  
![image](https://user-images.githubusercontent.com/32313919/135383816-430792aa-b8c3-4d6b-8176-1621293d089e.png)  
To answer a question type `!answer <question_number> "Answer"` in the #q-and-a channel. Example: `!answer 1 "Oct 12"`.  

![!qna](https://github.com/qchen59/TeachersPetBot/blob/main/images/gifs/createqna/qna.gif)


### Events/Calendar
Events are items relevant to a class that are time-sensitive. Currently, the types of events include office hours, exams, and assignments. Events in a class are kept track of, and assignments/exams are displayed in a calendar for students and instructors to see.

Events can be created by instructors. Creation of an event can be initiated in the private `instructor-commands` channel with the `!create` command. The bot will ask the instructor about various details for the event. Once the event is created, it should exist persistently within the system and will be added to the event list.

The calendar is updated at the creation of any new event that gets displayed on the calendar. Everything is ordered by date and sorted into two categories, past events and future events. Links attached to assignments are displayed in the calendar as well. The footer of the calendar is tagged with the last time it was updated.

![image](https://github.com/shikhanair/TeachersPetBot/blob/main/images/calendar.png)

### Office Hours
The bot contains functionality for handling TA office hours. After a TA office hour event is added and it is time for a TA's office hour to open, the bot will automatically create office hour channels in the server, allowing students to enter the office hour queue and instructors to help students based on the queue. Once the closing time for the office hour is reached, the channels related to the TA's office hour are automatically deleted.

![image](https://github.com/shikhanair/TeachersPetBot/blob/main/images/oh_channels.png)

### Polling
The bot contains functionality for polling with 2 choices (choose one) and multi-choice polling with specified number of choices (2 to 10). The polls can only be created by the Instructor and commands to create them can only be used in instructor-commands channel.

![image](https://github.com/qchen59/TeachersPetBot/blob/main/images/gifs/polling/poll.gif)

![image](https://github.com/qchen59/TeachersPetBot/blob/main/images/gifs/polling/multipoll.gif)

### Member Information
The bot contains functionality for getting information about a member using the username of the member. The command can only be used by the Instructor in instructor-commands channel. It retrieves the Display Name, ID, Account Creation Date and Time, Date and Time of joining the Server, Roles and the Highest Role of the member.

![image](https://github.com/qchen59/TeachersPetBot/blob/main/images/gifs/member_information/whois.gif)

### Take Event CSV
The bot contains functionality that lets Instructor get an example CSV from bot using !templates command and upload it back to the bot using !importevents command. This lets Instructor add all the events in one go.

### Notification Module
This command lets the user display all the homeworks that are due this week for all the courses. Whenever a user wants to be reminded about an upcoming project/assignment he/she can just use a notification command to get the bot to remind the user about the same. Notification can also be sent to email or text.

![!notifyme](https://github.com/qchen59/TeachersPetBot/blob/main/images/gifs/notifications/notifyme.gif)
![!notifyme](https://github.com/qchen59/TeachersPetBot/blob/main/images/gifs/notifications/notifyme.PNG)
![!notifyme](https://github.com/qchen59/TeachersPetBot/blob/main/images/gifs/notifications/notifyme2.PNG)


### Profanity Censoring 
Using the Python package better-profanity, Teacher's Pet will catch profane words sent by members of the guild, delete the message, and re-send the exact message with the bad word(s) censored out. It will also catch profane words in messages which have been edited to incude bad words. This package supports censoring based off any non-alphabetical word dividers and swears with custom characters. NOTE: Currently the Bot does not censor swears which have had extra alphabetical characters added.

![alt text](https://github.com/shikhanair/TeachersPetBot/blob/main/images/profanity_example.PNG)

<h2 align="center"> Releases </h2> 

-   [All releases](https://github.com/qchen59/TeachersPetBot/releases)

-   [v3.0](https://github.com/qchen59/TeachersPetBot/releases/tag/zenodo): First functional release
-   [v3.1](https://github.com/qchen59/TeachersPetBot/releases/tag/V3.1): Custom Events function
-   [v3.2](https://github.com/qchen59/TeachersPetBot/releases/tag/V3.2):Command specific voice channel creation and other bug fixs
-   [v3.3](https://github.com/qchen59/TeachersPetBot/releases/tag/V3.3): Parse uploaded csv
-   [v3.4](https://github.com/qchen59/TeachersPetBot/releases/tag/V3.4): Expand testing and API documentation



<h2 align="center"> What’s new in V3 </h2>

**Event creation improvements**

In V2, the calendar was not getting updated upon event creation. This has been fixed in the new version. Furthermore, the event creation subroutine is updated with looping and error checking. Now the user will not have to start over if they enter an invaid input. Also, users can now exit the process properly at any point by simply typing ‘quit’.

**Custom events**

Instructors of the course can now add custom events to the calendar. The database is updated to cater to this and the calendar is improved to have a new section called ‘special events’ to showcase custom events.

**Documentation improvements**

To better help the developers. The entire code base is updated to have docstrings of pdoc3 format and subsequently a new API documentation was generated. 

**Command specific voice channel creation**

Now teachers' pet bot supports command specific voice channel creation. Users can input the number of voice channels, the category name, the channel name, and max limit to create channels.

**Voice channel fix**

In V2, the teachers’ pet will report an error when generating the voice channels if there is a channel not in a category. We fix the auto voice channel creation bug in V3. 

**Get the channel Id when sending the notification**

In V2, the Teachers’ pet remainder is only functional in one specific channel from the original discord server(The server from the V2 team). In V3, we modified the method, so it can get the current channel ID and the remainder is working in a new channel.

**Parse an uploaded csv to check for reminders and events**

The previous group had started on this but it was, however we wound up essentially completely recreating the flow for how this feature should operate.

**Fix old unit tests**

The previous group was starting to transition their unit tests into another system. Their old system, where they used a separate bot to run tests, had a large number of issues such as not being able to see which specific tests failed when something was not working.
We transitioned the old unit tests into using the Dpytest library, which required rewriting almost all of them since the previous group had only converted 4 tests.



<h2 align="center"> Future Scope </h2>

- Track Participation of Students and their Ranking
- Sentiment Analysis of messages being sent on the server
- Attendance Tracker
- Conversion of bot to JavaScript
  - Data VisualizationExport data as graph(attendance)
  - Create a visualized table for events and remainders.
- Link Collection
- Calendar improvements 
  - When drawing the calendar, events without starting/ending times should indicate it specifically (or show nothing), instead of showing a 0.
-  Cloud Hosting
  - Upload bot to a hosting server, and also add bot to the top.gg, or discord.bots.gg



For a full list of future features, upgrades, and bug fixes, please visit our [Project 3 Board](https://github.com/qchen59/TeachersPetBot/projects/1).

<h2 align="center"> How to Contribute? </h2>

Check out our [CONTRIBUTING.md](https://github.com/shikhanair/TeachersPetBot/blob/main/CONTRIBUTING.md) for instructions on contributing to this repo and helping enhance this Discord Bot, as well as our [Code of Conduct](https://github.com/shikhanair/TeachersPetBot/blob/main/CODE_OF_CONDUCT.md) guidelines.

<h2 align="center"> License </h2>

This project is licensed under the [MIT License](https://github.com/shikhanair/TeachersPetBot/blob/main/LICENSE).

<h2></h2>

<h3> Team Members </h3>

[Qiuyu Chen](https://github.com/qchen59)

[Parth Jinturkar](https://github.com/ParthJinturkar)

[Yasitha Nisansala Rajapaksha](https://github.com/Arcane94)

[Hugh Wright](https://github.com/hughman98)

[Jiacheng Yang](https://github.com/Fishish)


