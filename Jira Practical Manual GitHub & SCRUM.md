# Course Practical Jira : Project With Agile / Scrum Methodology

# Content
- 1 [Introduction](#1-introduction)
- 2 [Getting Started With Jira](#2-getting-started-with-jira)
- 3 [Project Board & Settings](#3-project-board--settings)
- 4 [Jira List](#4-jira-list)
- 5 [List Navigator](#5-list-navigator)
- 6 [Epic & Roadmap](#6-epic--roadmap)
- 7 [Work Types](#7-work-types)
- 8 [Jira Query Language JQL](#8-jira-query-language-jql)
- 9 [Start Sprint](#9-start-sprint)
- 10 [Sprint Execution 1](#10-sprint-execution-1)
- 11 [Custom Dashboard](#11-custom-dashboard)
- 12 [Sprint Execution 2](#12-sprint-execution-2)
- 13 [Report](#13-report)
- 14 [End Sprint](#14-end-sprint)
- 15 [Workflow](#15-workflow)
- 16 [Jira & Slack](#16-jira--slack)
- 17 [Jira & GitHub](#17-jira--github)
- 18 [Bonus & References](#18-bonus--references)

![Name](pics/name.png)

## 1 Introduction
[⬆ Back to top](#top)




[⬆ Back to top](#top)

## 2 Getting Started With Jira
[⬆ Back to top](#top)

This section will explain what jira is and why it is so popular. Jira is a product of atlassian company.Atlassian itself has a wide range of software groupedinto several categories. These software have their own function and are sold as separate products.In this course, you will focus on using jira.

Jira itself is software for managing projects or tasks.It can be in the form of project status, distribution of tasks, tracking task status, or tracking issues or bugs in software development.

Why do you need Jira? Project management is needed so that a project can be planned and implemented properly. The tools used are usually spreadsheets such as Excel or google sheet to track about the status of tasks, processing time, issues, and other things.But spreadsheet is not a specific tool used for project management. Their function for project management is limited.Especially in agile projects, using spreadsheets might requires more effort.This is where jira fits.Jira has been around for a long time, with complete features and specifically designed for project management.Jira is very useful, relatively easy to use.

This made jira popular.Even though it is closely related to an agile brand, jira can be used for various functions or work management models. Jira can also be customized according to each company's needs.

Jira has many additional applications, either free or paid, that can be used for jira customization, as well as jira integration with other products, even with products outside of Atlassian.

At the time of recording this video, there were two versions of jira that could be used.First is jira cloud,where you rent jira in the cloud which you can use immediately. You don't need to do any installation or maintenance.In the cloud version, you can make monthly or yearly payments.Jira cloud also provides a free version that can be used for small teams. There are some companies that choose to do the installation and management of jira themselves.

Maybe for reasons of data confidentiality, or because of company regulations. For this, jira provides a datacenter version of jira,where the company bought jira server,installing in the company's own data center, and managing jira itself.

In this course, you will use the free version of jira cloud.At the time this video was made, the free cloud version of jira can be used by up to 10 users and the functions are also quite complete.However, this free jira may change at any time according to atlassian's policy.Therefore, always check Jira prices first on the official Atlassian website. To start using Jira, you can register first on the Atlassian site.

In this course, you will practice using jira for the scrum method. Scrum in short is a work method, where you have a product backlog, which is a list of features that will be worked on for a product, for example in a mobile application, the backlog can be in the form of login features, search features, payment features, and so on. 

These features are usually known as user stories.Within a certain period of time, for example every Monday every 2 weeks, a sprint planning meeting is held, namely a meeting to take features from the product backlog that will be worked on, and completed, in 1 sprint.Sprints are periods of fixed length, usually between 1 and 4 weeks. But each team will take a standard that is fixed, for example team X's sprint period is 2 weeks, while team Y's sprint period is 4 weeks. The features that will be worked on in the sprint will be moved from the product backlog to the sprint backlog.Every day during the sprint, there will be a daily stand up process, which doesn't take long, try to make it less than 30 minutes, for regular updates to all team members about the process that has been done, and whether there are any obstacles. At the end of the sprint, there will be a sprint review and retrospective, in short an evaluation of the running sprint. Here ideally all the sprint backlog is complete.you will see how to use jira in this scrum method.
![SCRUM](pics/scrum-process.png)

### Task
Register to atlassian and create a Jira project with Scrum template, and type Team-managed - https://www.atlassian.com/

### Guidance
- Go to the atlassian website
- Register using your gmail or work email
- Create a Jira project with Scrum template and type Team-managed

### Solution
To use jira cloud, you can open atlassian.com and look for the menu to try jira software. You will start with jira software first. Navigate to the screen where you are asked to enter your email. In this example, you will use gmail to create an account. Enter the address for your jira. Usually this is the company name or team name. Click this button and wait a moment until your jira is ready. You will skip this section until the “Add Workspace" screen.

Here you can choose a template for the project. Jira provides many templates, but in this course you will be using Scrum templates, which are commonly used for projects with agile methods. 
![Jira Templates](pics/jira-templates.png)


Then choose team-managed, where this type is suitable for independent teams, so it is suitable for this course. Company managed is more suitable for use when teams within an organization must follow standards that apply to all teams in that organization. Name this project. For example, I will create a project "My car Project". Then create the project. 

Skip the optional sections. You can go to the workspace, from the menu on lefft. Select your work for the project you are involved in, or select spaces to see all existing workspaces.

![Workspaces](pics/spaces.png)


[⬆ Back to top](#top)


## 3 Project Board & Settings
[⬆ Back to top](#top)

Each workspace has a board, which shows what tasks need to be done, and the status of each one Each board will have several columns where each column usually indicates a status. The column defaults for jira are “To Do”, “In progress”, and “Done”. You can remove, change, or add columns as needed. These columns are usually arranged in order from left to right, where the more to the right, the closer to complete.

You can also add your team members on each board, so that each team member will collaborate using the same board.

Every workspace in jira has some features, for example for boards, reports or other features. Some of these features are on by default, but you can also turn them on or off as needed. You can also manage other things through project settings, for example email notifications, access to projects, and so on.

### Task 
Make a workspace board with the following columns (order from left to right)
- To Do
- Development
- Code Reviews
- SIT
- UAT
- Done

Enable features for:
- Reports
- List

Add 2 team members to the project

### Guidance
Use the Board menu, where you can:
- change column title
- add column
- drag-drop to adjust column order

To enable / disable features, use the Workspace Settings > Features menu

To add team members, you can do it from the board, or from the Workspace Settings > Access menu

### Solution
To see the workspace board, you can click on workspace project menu on left. Here you can see all jira workspaces that you can access. Each workspace will have a board. 

Click this board to enter. you can rename the column. For example, you can change the in progress column to "UAT" or user acceptance test. To add a column, you can go right and click this button.

Let's add a column:
- SIT or system integration test, Development,
- Code Review.

Then to sort the column, you can drag-drop with the mouse. Let's sort from left to right: To do, development, Code review, SIT, UAT, Done.

![Workspace Board](pics/bard-structure.png)

You can also set many things from workspace settings. For example, to set columns, you can also go to workspace settings > board > columns and statuses.

You can also activate or deactivate features such as notifications, or built-in jira features.

For example, let's go to workspace settings > features, and turn on features for reports and list navigators.

After you turn it on, there will be 2 new menus on the active left side.

To add your team member to the workspace, you can click this button on the board. Or you can go to the workspace settings, select access, and add your team members.

Let's add 2 team members. Here you will use a fictitious team member. I will add two users that I previously registered with jira. You can create an email with another account, and register with jira. The team member you invite will receive an activation email. They have to click and confirm the invitation.

Switch to administrator user and give these user rights fomr Workspace Settings/Access.

[⬆ Back to top](#top)


## 4 Jira List
[⬆ Back to top](#top)

Jira List is used to represent a task that must be completed.

This List indicates : what needs to be done, the status of the work, who is responsible, and so on. For example an application functionality that must be completed, incidents or bugs in the system, creation of user manual documents, and others. This can be anything, as needed. Even if you are using jira for a project that is not related to software development, you can create an work item, For example, to track permits that must be done to open a business.

Each work item can be in a certain status, indicated by the column on the board. For example, if there are todo, development, and done columns on the board, then each column will become a status of the work item. You can move the work work item or change its status, so it's clear where the process is for the work item.

You can also make an estimate of how long it will take to work on the work item. In the Scrum work process, this estimate usually uses story points. 

In the Scrum method, there is a term user story. This is a task that must be done, which has been broken down into one small part that has a clear functionality. In jira, story is a type of an work item. You'll learn about jira work item types later, but for now it's enough to understand that a user story is basically one of the work item types in jira.

You can use this table to estimate using story points. A story point with a value of 8 or 13 means that the user story is too large in scope, and should or must be broken down into more than one user story.
![Story Points](pics/story-point-table.png)

The user story or work item that is currently being worked on is placed on sprint backlog. User stories that not started yet, can be placed in a product backlog. User stories in the product backlog could be worked on later because the priority is lower, the requirements are not clear, or they may even be reconsidered and possibly cancelled.

One user story can have several subtasks, namely a user story fragment that has a more specific scope, but all of these subtasks need to be completed so that one user story is considered complete. For example, you can divide the login user story into two subtasks: 
- frontend, or display
- backend or coding logic for the process

You can also link one user story with another user story. For example, if you have a user story for the login function, but to do this login function, you need a user story related to the database preparation, then you can link the two user stories, so it's clear that they have a dependency.

The format for writing a user story can be anything, but in software development, the format commonly used is BDD or behavior driven development. There are 2 sections in a bdd user story, usually using the following format:

Narrative, which is what should be done in this story, by whom, what is expected from the completion of this story. And one or more acceptance criteria, which is specific scenarios related to the narrative.
![User Story Content](pics/user-story-content.png)


Here is an example

![Example User Story](pics/example-user-story.png)


### Task
Create a user story for login, with two subtasks:
- Frontend login, with 3 story points, assign to team member X, label it as android and iOS
- Backend login, with 3 story points, assign to team member Y, label it as backend

For user story, add new fields:
- cost estimation
- priority

Clone the user story login to user story home screen. On the user story home screen, create 3 subtasks.

Mention team member X in an work item comment.

### Guidance
- To add work item, use Backlog menu
- To add a subtask, use Related Work section in each work intem details
- To add field, use menu Workspace Settings > Work Types
- To clone, select context menu (...) on the Work Item screen
- Comments for Work Item are at the bottom of each Work Item
- To mention team members, you can use @username-team-member

### Solution
To create a user story in jira, you can go to the backlog menu. Add a user story, for example, a login function. Select the type of issue, which is story. Fill in the title. Now fill in the user story.

You can click the backlog, then click the work item title to work with full screen view. You can provide user stories in an easy-to-read format, just like typing. For example, to make text bold, use ctrl B. You can also use this toolbar for editing, inserting images, and so on. So this editor is easy to use, just like you work using Microsoft Word or Google Docs.

![Login Work Item](pics/login-work-item.png)

In this section, you can provide details about the user story, for example, who will be assigned to it, estimated story point, and so on. Screens for work item on Jira, can be customized as needed.

![Login Work Item](pics/login-item-details.png)

Click this section and select configure. Or you can also go to workspace settings, select work types, and select the type of work item that you want to customize. 

![Work Types](pics/work-types.png)

For example, you can add a "priority" field, or even a custom "cost estimation" field.

![Story Fields](pics/story-fields.png)

To add a subtask, click on the "+" button in the 'Related work' section in any work item. For example, let's create a subtask "frontend login" and assign it to the jira one user. Also the “backend login” subtask and assign to the jira two user. Let's give each subtask story points. 

![Story Subtask](pics/story-subtasks.png)

You can also provide labels or tags for each issue, which is useful for grouping work items according to your need. For example, let's give “android” and “iOS” label in the login frontend subtask. For the “backend login” subtask let's give it a “backend” label. 

![Frontend Login Subtask](pics/frontend-login.png)
![Backend Login Subtask](pics/backend-subtask.png)

You can also make a clone of a user story. For example, clone the user story login to create a user story home screen. This clone is useful if you have an work item that is similar to an existing work item.

Let's edit accordingly. For example, the description and priority can be changed. You can also add child work item or subtasks. For example, add 3 subtasks, give each story point, and assign it to a team member. 

![Homescreen Work Item](pics/homescreen-work-item.png)

Here you can also see that one story can be connected, or linked, with another user story. You can remove or add a user story link.

Every work item in jira can be commented on, so you can communicate with other teams regarding the work on this work item. For example let's go to the login frontend subtask and leave a comment. To mention team members, you can start with the @ sign and type in your team username. For example mention jira one.

Let's login as jira one. Here jira one will get a notification if his name is mentioned. Jira One can reply to comments on the same issue, and can mention team members too.

Let's go back to the first user.


[⬆ Back to top](#top)


## 5 List Navigator
[⬆ Back to top](#top)

Jira List is a very important part of Jira. Because of that there is an list navigator screen. In this screen there are several functions: To do bulk updates, or update many work items at once.

Import work items from files in csv format. You can also look for issues in a simple way, or using JQL or Jira Query Language.

Jira list navigator will not appear by default. you have to activate the list navigator first via the workspace settings menu > features.


### Task
- mport CSV file containing issues. For CSV file sample, you can download the last part of this course in the Bonus & Reference section, or you can use your own CSV
- Use bulk change feature : add comment to several issues at once
- Activate Issue Navigator and explore how to use the it to search for issues

### Guidance
- Activate the list navigator menu from Workspace Settings > Features
- You can import CSV and change many work items at once from the List > ... menu (top right)
- Search work item from menu list



### Solution
To import issues from a csv file, or a comma separated file you can click on these three dots. Then select import from csv.

![Import Work Items from CSV](pics/import-csv.png)

This is an example of the CSV to be imported. Or you can create your own csv. You can download a sample csv in the last part of this course in the lecture with the title Bonus & Reference - sample-data-jira.csv. Make sure the csv you choose, its first row is the column header. There is no special format, column order, or constraint.

You will map the csv to jira each time you import it. Choose to import this csv into my car workspace. Then you will map each CSV column to a jira field. You can do the mapping as needed, or even ignore the column. For example:

CSV details will be imported into jira issue description The title becomes the issue summary. PIC becomes assignee Meanwhile, you will not import the status in the csv.

![Import Work Items from CSV 1](pics/import-csv-1.png)
![Import Work Items from CSV 1](pics/import-csv-2.png)
![Import Work Items from CSV 1](pics/import-csv-3.png)

You can validate first before importing. Here you will see that the user "Jira One" is apparently not registered because for import assignees in jira, what is recognized is the user's email.
![Validate CSV](pics/validate-csv-1.png)

Here you have two options: change the Jira user in CSV to an email. Or do value mapping through the import screen. 

![Validate CSV](pics/validate-2.png)

Let's go back to the field mapping section, and click on mapping value in the PIC section. Map user "Jira One" to the user email.

![Mapping CSV](pics/mapping-imports.png)
![Mapping CSV 2](pics/mapping-csv-2.png)

The other user already using email, so you dont need to map Jira Two user. Try validating again and all work items will be able to be imported. Start importing it.

![Validated CSV](pics/validated-csv.png)

Check the backlog screen again and you will see the work items that were just imported. Return to the list navigator screen. 

![Backlog with Imported Items](pics/imported-items-backlog.png)

You can update many work items at once. For example, let's add comments for newly imported work items.

From the List navigator, select three dot menu and click on 'bulk change work items'. Select the work items to change.

Here there are many changes that can be made:
- edit work item
- moving issues to other workspaces
- changing work item status
- deleting work items

You can also watch work item, so every time there is a change in an work item you will get a notification. Or vice versa, unwatch issue to stop notifications.

Let's try to edit the work item. Add a comment: "Import result". You can edit multiple fields at once if needed. Click and do bulk update. 

![Bulg Work Items Update](pics/bulk-update.png)
![Bulg Work Items Update 2](pics/bulk-update-2.png)
![Bulg Work Items Update 3](pics/bulk-update-3.png)
![Bulg Work Items Update 4](pics/bulk-update-4.png)
![Bulg Work Items Update 5](pics/bulk-update-5.png)
![Bulg Work Items Update 6](pics/bulk-update-6.png)

Now if you open the work item that were recently modified there will be a comment "Import result".

![Bulg Work Items Update 7](pics/bulk-update-7.png)

You can also search for work item via the list navigator. The screen is quite easy to use, for example if you want to find all the work items assigned to a user, you can click this dropdown and select the specific user. 

![List Filters](pics/list-filter.png)

Or if you want to find all subtasks, you can select them in the items type. 

![List Filter Subtasks](pics/list-filter-subtasks.png)

Actually, to look for work items, it doesn't have to be from the list navigator. At the top there is a textbox for search, where you can search for the keywords you want. For example, search for the keyword "car". And jira will search for things that match the keyword. Not only work items, even boards can also be searched, and you can also search with the several parameters provided. This textbox is smart. For example, if you want to search keyword subtasks, you can just type "subtask" and the search textbox will show only the matching keyword.

It's just that in the list navigator, the search parameters can be more complete. For example, you can add a search filter “created date” to find all work items created 2 hours ago.

![Custom Filter](pics/create-custom-filter-2-hours.png)

If you want to search only for work items that contain a certain word, you can add the word in 'Search work' textbox. Not only looking for work items, in the list navigator you can export work items for example as html, microsoft word, or other formats.

![Export Work Items](pics/export-work-items.png)


[⬆ Back to top](#top)


## 6 Epic & Roadmap
[⬆ Back to top](#top)

In agile methods, there is the term epic. Epic is a big job or feature to do. An epic is a grouping of several relevant user stories. For example epic for search function, where there is a user story to find a car, sort search results, and send search results to email. Remember that each user story can be further divided into smaller subtask, each of which can be completed in one sprint. So hierarchically, it would be as follow:

![Work Items Hierarchy](pics/work-items-hierarchy.png)

However, this diagram does not have to be followed exactly the same. So you can have a user story without subtask or epic. It's just that with a hierarchy like this, the work will be more structured. 

If epic is feature, then the combination of those features will be released as a product. A product can have a roadmap, which shows the big picture of that product, and when a certain epic will be completed. You can change the estimated epic complete date from the roadmap, and perform project control based on the roadmap.


### Task
Make the following epics and add relevant issues (story) into the epic. Make sure all user stories is part of an epic.
- Search
- Maintain user
- Maintain car
- Home screen

### Guidance
Create epic from Create button at the top, or press C on the keyboard

Adding issues to epic can be done from epic details in the Backlog or issue navigator. To display epic in the backlog, you must turn on the epic panel (on the Backlog screen)

### Solution
To create an epic, you can click the create button above. Or simply press the C key on the keyboard.

Select epic for the issue type. For example, create an epic for the "Search Feature". 

![Create Epic 1](pics/create-epic-search-feature.png)

Now go to the List navigator and you can see that there is a new epic. 

![Create Epic 1 Result](pics/created-epic.png)

If you go to the backlog, the epic is not there. To display epic in the backlog, you can turn on the epic panel from this button.

![Enable Epics in Backlog](pics/enable-epics-backlog.png)

Here there will be issues without epics, and new epics that you have just created. To add user story work item to epic, there are several ways. For example to add the user story "Search for a car" to epic, go to epic detail, then add a child items.

![Epic Details](pics/epic-details.png)

You can select an existing user story, or even create a new user story.

For example, add an existing work item. Or add a new user story: "Send search results to whatsapp". The second way is through the List navigator.

![Epic Details 2](pics/epic-add-child-item.png)

Try searching for work item which contains word "search". Then select bulk update. Modify all user stories. Edit work item. Change its parent to epic for the search feature. 

![Items and Epics](pics/bulk-imtems-epic-update.png)
![Items and Epics 2](pics/bulk-items-with-epic-1.png)
![Items and Epics 3](pics/bulk-items-with-epics-2.png)
![Items and Epics 4](pics/bulk-items-with-epics-3.png)
![Items and Epics 5](pics/bulk-items-with-epics-4.png)


Now if you look at the epic again, there will be several child items.

![Items and Epics Result](pics/bulk-items-with-epics-result.png)

Try opening one of the user stories, and you can see in the navigation section that this issue is part of the epic "Search feature".

Try adding another epic for the "Maintain user" feature and add stories related to the user into the epic
- Register user
- login
- change profile
- logout

![Maintain User Epic](pics/maintain-user-epic.png)


Then epic for the "Maintain car" feature. Add user stories related to adding cars, deleting cars, and contacting car seller. 

![Maintain Car Epic](pics/maintain-car-epic.png)

Finally, add an epic "Home Screen" and enter a user story for the home screen so this epic only has one user story. 

![Home Screen Epic](pics/homescreen-epic.png)

You can also change epic details, for example changing the color.

![Epics Color Edit](pics/epic-color-edit.png)

The result of the Epics configuration:

![Epics List](pics/epic-list.png)

Timeline is already a default feature of jira. Click on the roadmap menu and you will see all the epics in Jira. You can change the estimated start and finish dates of epic using mouse. You can also see stories in an epic.

![Timeline](pics/timeline.png)

Here you can also change the time dimension of the timeline whether daily, weekly, monthly, or even quarterly with the bottom of the screen menu.

![Timeline Periods](pics/timeline-period-menu.png)


[⬆ Back to top](#top)


## 7 Work Types
[⬆ Back to top](#top)

### Create custom work type:

Space Settings Menu / Work Types / Add Work Type:
  - Name: Manual Process
  - Description: 
  - Set Icon
  - Create

Set fields to the custom work type
  - Priority
  - Assignee
  - Labels
  - Due Date
  - Save Changes

In the workspace create new work item with the custom type
  - Create
    - Space: Space_name
    - Work Type: Manual Process
    - Summary: Create User Manual
    - Craete

In the Backlog we can see the newly created cutom work type item. We can assign the custom work type to any epic as with the standard work items.


[⬆ Back to top](#top)


## 8 Jira Query Language JQL
[⬆ Back to top](#top)

In addition to the basic search features, jira issue navigator also provides more complex search using the Jira Query Language. If you are a person who knows about SQL or query language for databases, then JQL is like SQL. You type what you want to search for, using a language that Jira recognizes. Using basic search on the issue navigator is actually enough for daily work. So this section is optional, you can skip this section if you don't need to know about JQL.

### Try JQL to find all stories assigned to a particular user, ordered from the oldest
To access JQL, you can go to Space / List / Filters / Advanced / JQL
  - project = SCRUM and type = Story and assignee = assigned_user ORDER BY created ASC

For details on languages that can be used in Jira, you can see the reference document at the end of this course, in the section with title “Bonus & References”.


[⬆ Back to top](#top)


## 9 Start Sprint
[⬆ Back to top](#top)

Sprint in the agile method is a fixed period of time to work on, and complete backlog. These sprints can vary between teams, usually between 1 to 4 weeks per sprint. But each team should choose a fixed timeframe for that team, for example team A's sprint period is every 2 weeks, while team B's sprint period can be 3 weeks.

At the beginning of the sprint, a sprint planning is held, where the team will plan together, which stories will be taken from the product backlog, and how much effort is needed to complete each. So 1 person might be able to complete several light stories, or even 1 person complete 1 story that is quite heavy in that sprint. This estimate is recorded as a story point. The goal of the sprint is to resolve the issue at the end of the sprint, so if there is 1 story that takes a long time, more than 1 sprint to complete, then that story is too big and must be broken down into smaller stories, where these small stories are taken and completed one by one.

Once you have a product backlog, the next step is to take some of the product backlog into a sprint backlog. For example, if the length of 1 sprint is 2 weeks, then take the issues that must be completed within 2 weeks. It is important here that you break down a problem into smaller parts. In the scrum method, you ideally produce something in 1 sprint, so if there is one issue that turns out to be big and takes more than 1 sprint, then that issue should be broken down into several smaller issues, and resolved gradually. Each issue will be given an estimated weight, usually using story points. Jira is perfect for agile methods, where processes in Jira already have a product backlog, sprint backlog, and story points. 

In order for the sprint plan to run well, it's best to take issues that have clear requirement in the product backlog. So it's clear input, output, and validation of a story. In other words, the narrative and acceptance criteria should already exist when the sprint plan is held, so the sprint plan is done to explain the narrative and acceptance criteria, not to create them. Because of that there is usually a sprint grooming before the sprint plan, where not all teams are involved, only the product owner who responsible for the user story, and it could be together with the technical lead from the team, so that the narrative and acceptance criteria can get input from a functional and technical perspective.

In sprint grooming, priorities can also be made, which ones will be taken from the product backlog to the sprint backlog

### Task
Move some stories to the sprint backlog, then start the sprint with 1 week period. Provide estimated story points for each issue in the sprint backlog.

### Guidances
Moving issues and starting sprints can be done from the backlog. Story point is a field in each issue.

### Solution
Go to Space / Backlog

In the real life, you should have sprint planning. But in this video you'll pretend the sprint planning is already in place, and you'll focus on using jira.

For example, in the sprint plan it was decided that the epic for maintaining the user and home screen would be done first.

Then you can move issues from the product backlog by dragging issues. 

- Move 'Login' Story to Sprint 1

You can also select multiple issues at once by pressing the shift or control key on the keyboard, then clicking. Apart from sliding, you can also click on the three dots on one of the selected issues, then an option will appear where to move the issue.

- Select and move 'Homescreen', 'Register User ' and 'Change user profile' to the sprint at once.

You can do the same thing in the sprint backlog, selecting and moving issues to the product backlog. Or in the sprint backlog itself, you can move issues to make them easier to read.

To provide an estimation of the story point, make sure the story point field already exists in the issue type.

You can check from space settings / work types / item / item point estimate

if there aren't any story points field yet. Let's give a story point to each work type.

For issues that have child issues, such as login, you can provide story points to subtasks, because this subtask is the smallest part of an issue, which must be resolved.

You can change sprint data, including story points in the middle of a running sprint. However, this is a bad practice in agile methods because it means that the sprint plan estimate is not planned carefully. 

If you have finished selecting issues to work on in the sprint backlog then click this button to start the sprint.

![Start Sprint](pics/start-sprint.png)

Here you can fill in sprint details: sprint name, period, and notes.
![Sprint Details](pics/sprint-details.jpg)

After you start the sprint, you will be taken to the sprint board. Here note that the selected issue will appear in the to do section. But the subtask is not showing. To display subtasks, you can select the "group by" dropdown and select subtask.
![Board Subtask View](pics/subtask-view.jpg)

In this section there is also an insight button, which function is to see how far the process in this sprint has progressed.
![Sprint Insigths](pics/sprint-insights.jpg)

On this board you can also use simple search,for example displaying issues that are assigned to certain people. Or search for issues by epic, or label, or issue type.
![Sprint Filters](pics/sprint-filters.png)

This sprint board should be used by every team member in the sprint implementation process, and each team member must be proactive in updating their respective tasks.


[⬆ Back to top](#top)


## 10 Sprint Execution 1
[⬆ Back to top](#top)
After the sprint starts, jira will create a board that shows the status of the issues in that sprint. During the sprint, each issue on the jira board must be actively updated by the relevant people, so that it is clear where the status of this sprint is. Each person can login to jira, access the board menu, and perform several actions, such as commenting or changing the status of an issue. These issues will be used as input reports in jira, which you will see later. 

Because of that it is important to establish a work habit where all team members proactively update issues, especially status.

For example, this morning someone worked on an issue then that person has to change the issue to the appropriate status. If during the afternoon, the status changes, that person must also update the issue to a new status.

### Taks
Login as another user which has issues assigned, then move the issue to be worked on to the appropriate status.

### Guidance
You can move the issue status from the board menu, then drag the issue to the appropriate status column. Or it can be done from the status dropdown in each issue.

### Solution
Let's login as another user, who was assigned some issues. Go to the sprint board, and try to display the issues assigned to this user, including their subtasks.
![Role View](pics/role-board-view.jpg)

To move an issue, you can drag the related issue to the appropriate column. For example, let's move the login frontend to “Development”. You can also click on an issue to change details, leave a comment, or change status. Jira is not limiting which fields can or cannot be changed after the sprint has started. So whether or not a field could be changed is a team practice that must be agreed upon.

In general, things related to the sprint story points, should not be changed. Team can give any comments here, including mentioning other team members. Or if it turns out that a different team member has been assigned then the assignee can be changed.

Issue will be considered complete if it is entered in the done column. When you move issue to another status that is not done, and see insights there will be no changes. But if you move something to done then the insight will change.

[⬆ Back to top](#top)


## 11 Custom Dashboard
[⬆ Back to top](#top)

In jira, you can create a dashboard for reporting purposes. There are many components, or gadgets, provided by jira for this purpose. Dashboards can be dashboards for a project, active sprints, or you can create dashboards to display data according to your own criteria, using filters.

Access rights can also be set on this dashboard, whether only you can read it, or your team. Or anyone who can edit. You can also create your own criteria that can be used on the dashboard. This criterion is referred to as a 'filter'.

For example, if you want to create a dashboard for each of your team members, then you create a filter for each team member, and create a dashboard from that filter. Creating filters can be done from the List navigator, where you search for items based on the criteria in the navigator, then save those criteria as filters.

### Task
Create dashboards to know:
- issue statistics (how many % are in status X, how many % are in status Y, etc.)
- pie chart that displays the number of issues for each team member, and the number of issues that have not been assigned
- calendar contains the due date for completion of issue

Create dashboards to know:
- sprint statistics (how many issues on progress, issues completed)
- burndown chart
- issue type statistics (how many tasks, subtasks, issue type X)

Create a custom filter & dashboard to display only issues assigned to a particular team member

### Guideance
Create a dashboard from the dashboard menu. You can use components (gadgets) which are provided by Jira, as needed.

### Solution

To create a dashboard, click left bar menu and select create dashboard. You can also select the view all dashboard menu to see all existing dashboards. 

![Dashboard Location](pics/dashboard-location.png)

Let's create the first dashboard. Give it the title "My Team Dashboard". Here you can manage access to the dashboard, who can see, and who can edit. Since this is the dashboard for the team, let's give viewer access to all the team members in the project. But for editors, keep it private, so only you can edit.

![Dashboard Create Settings](pics/dashboard-create-settings.png)

Jira already provides the components, or gadgets, for creating great dashboards. There are dozens of gadgets provided, and you can add the gadgets you need to this area. 


As an example, let's add an "Work Item Statistics” gadget.

![Gadget Search](pics/gadget-search.png)

For the input, use my car project. You can choose what statistics you want to display for example, you can display them based on the issue status. You can also set other fields according to your needs. What's interesting, here is an auto refresh feature, so the data will be updated automatically every few minutes. Try enabling this feature.


So now you have a visual display, how many issues are still in todo status how many are in development, and so on. If there is a change in data, for example there is an issue that changes status, this dashboard will also change its percentage.

Let's add another gadget below that, now look for the “Pie chart” gadget. Choose my car project. And display by assignee. So that you have a chart view of each person's workload or issues that have not been assigned.

You can click on these three dots to change the chart name for example to "Task assignment". Or change the color of the bar. Furthermore, you can even click on the name of an assignee, and you will go to the issue navigator, where jira displays data according to the assignee you selected.

Try adding one more to the right, this time adding the “calendar” gadget.

![Calendar Gadget](pics/calendar-gadget.png)

Select to display “Due date”. Rename this gadget to "Issue Due Date". If you look at the calendar, there are markers about issues that are due. You can move the mouse over the marker to see which issue is due.

![Calendar View](pics/calendar-view.png)

It does not looks too good, because the calendar is too small. You can change the layout of the gadget using layout button. Let's turn this into two columns, with the right column being larger. Click done.


Apart from configuring auto refresh on each gadget, you can also click on this three dot menu and configure auto refresh for all gadgets.
![Automatic Refresh](pics/automatic-refresh.png)

For example refresh every 30 minutes.

![Automatic Refresh 2](pics/30-min-automatic-refresh.png)


Try making a second dashboard about sprints. Name it “My Sprint dashBoard” and give access to the project team. 

![Sprint Dashboard](pics/sprint-dashboard.png)

Try looking for gadgets that have the keyword “Sprint”. Add sprint remaining days to dashboard.
![Sprint Gadget](pics/sprint-gadget.png) ![Sprint Gadget Settings](pics/days-remainding-gadget-settings.png)

In 'sprint health' and 'sprint burndown' there are configuration options to display which sprints. Select the next sprint, so this gadget will display the running sprint data.

![Sprint Health Gadget](pics/sprint-health-gadget.png) 
![Sprint Burndown Gadget](pics/sprint-burndown-gadget.png)

The lower right is still empty let's add a "heat map" gadget to see the distribution based on issue type.
![Heatmap Gadget](pics/heatmap-gadget-settings.png) 

The bigger the text size, the more issues that exist in that type. Change the layout so that the part with the chart is bigger. Click done, and now you have two dashboards showing reports about your work.
![Sprint Dashboard 2](pics/sprint-dashboard-2.png) 

Now let's try to create a filter. For example, you want to create a filter for one of your team member. Go to the issue navigator, which can be basic or JQL and select the issue whose assignee is some of users. Then save it as a filter.
![Work Items List Filter](pics/work-items-filter.png) 
![Custom Filter](pics/custom-filter.png) 

Name it as “Jira One Filter”. Just like the dashboard, you can also set access rights for using this filter as well as who can change it. Filters will be accessible at the left, via the filter menu.
![Filter Menu](pics/filter-menu.png) 

Now try to create dashboard again. Call it: “Issue for Jira One”. Try adding a gadget, for example "Work Item Statistics". Now you can select not only projects, but also filters. So if you use the "jira one filter", the issues that will appear on the dashboard are only the issues assigned to jira one.
![Dashboard with Filter](pics/custom-filter-statistics.png) 

Try it, make it with statistics type "Status". And this dashboard will display data based on filters. Save the dashboard.
![Dashboard with custom Filter View](pics/dashbard-with-custom-filter.png) 


[⬆ Back to top](#top)


## 12 Sprint Execution 2
[⬆ Back to top](#top)

Sprint is a plan, and execution should follow the plan. But that doesn't mean that the plan is completely unchangeable. For example, if in the middle of a sprint it turns out that there is something that must be done immediately, because it is related to government regulations, then the sprint can change.

However, something like this should be agreed by all parties involved, and everyone understands the consequences, maybe there is one job that was planned at the start of the sprint, must be delayed. 

Things like this are the policy of each team, but what we will discuss is that Jira can also accommodate the change process in running sprints.

### Task
Change the story point by adding an issue to the running sprint, or vice versa: removing the issue from running sprint. Create an issue in with type bug and link it to a user story.

### Guidance
- Add / remove issues from running sprint using backlog menu
- You can create bug from the backlog or press the C key on the keyboard, then choose the issue type : bug
- Linking issues can be done from button Link in each issue

### Solution
For example, currently the sprint is running and there are several issues that are being tested, some are still being developed, and so on. At this point, the sprint is running. But apparently there is additional work. Let's say there is a new request for uploading car videos. In sprints, the addition of story should agreed among the parties involved, whether the new story will be worked on running sprint or not.

Let's say in this example, the car video story will be worked on, and it needs 5 story points. Go into the backlog, and add that story. Since it's going into a sprint, move from the backlog to the active sprint. Jira will notify you that the sprint will be affected. This is because the sprint is a plan: what will be done, hence additional work after the plan can have an effect on the sprint, for example that there are more effort to do. It's okay, we'll try it. 

![Upload Car Video](pics/upload-car-video-added-to-sprint.png)

Or it could also be a bug was found during testing. You can add an issue with bug type. Since this issue is a bug which should be fixed in the same sprint, let's add it to this sprint.

You can create the issue directly on the sprint. Since bugs are usually related to story being tested, you can choose to link this issue with the user story issue. On link issue, there are several types to choose from.
![Bug Link](pics/link-bug-to-items.png)

This type is informational, but since bug usually hinder user stories let's choose accordingly, that this bug blocks user story.
![Bug Link Settings](pics/bug-item-settings.png)
![Bug Link Settings 1](pics/bug-item-linked-item-1.png)

This link works two-ways, so if we open the user story, a link will also appear in that user story that this particular story is blocked by a bug issue.
![Bug Link Related Item](pics/related-bug-work-item.png)

Changes are not just additions. It could be, for example, that certain issue is pending, maybe because it need to purchase a product, and the purchase of the product takes one month. For example, let's move one of these issues back into the backlog.
![Item To Backlog](pics/work-item-to-backlog.png)

[⬆ Back to top](#top)

## 13 Report
[⬆ Back to top](#top)

In Scrum method, there are several reports that are commonly used. The most common is probably burndown chart, which shows the planned versus actual work during the sprint. Then the velocity chart, which shows commitment to work versus actual work after the sprint ends. Jira provides then as built-in reports. If the report menu isn't there yet, you can activate them from project settings > features.

### Task 
Watch and learn these reports: burndown chart, burnup chart

### Guidance
If the report menu isn't exists, enable it from Project Settings > Features

### Solution

I will move Logout issue to done status, so we have data sample. Open reports. First we will look at the burndown chart.
![Report Burndown Chart](pics/report-burndown-chart.png)

In the incomplete issues section, you can see which issues that is not started or still in progress. In the complete issue section, you can see which ones have been done.
![Burndown Chart Sections](pics/burndown-chart-sections.png)

And there is the “Scope change” section. This section shows if there are changes, such as adding issues in the middle of a running sprint. Here you can see the details, for example if you work based on story points then how many story point changes. In ideal sprint, this scope change should be minimal or not exists.
![Report Burndown Chart Changes](pics/report-burndown-chart-scope-changes.png)

The chart above is known as burndown chart. The vertical axis shows the total number of story points in the sprint. The horizontal axis shows the sprint date. This gray line is a guideline, showing ideal conditions, where every day there is a story point that is done, or the term "burnt".So if there are story points that are burned, the remaining story point will decrease and finally at the end of the sprint it will be zero. The red line is the actual condition. It could be that the user story is still in progress, or hasn't been started at all. A user story that has moved to the “Done” state will “burn” the story point, and the red line will drop.

![Report Burndown Chart 2](pics/report-burndown-chart-2.png)

In the contrary, if there are additional user story points, this red line will increase. Therefore changing the scope in the running sprint will make the red line move away from the gray guideline. In an ideal sprint, the red line will descend, near the gray, or even below the gray. 

Try going to the board, then move 'upload car video' work item to done status. Then look again at the burndown chart and you will see that the issue that just moved to done

is burning the story point, so that the red line is decreasing. If there is a burndown report, then there is also a burnup report. Actually, these two reports display the same two pieces of information which is work guidelines and actual work. It's just that burndown reports start from many to zero, burnup reports vice versa, guidelines and actuals start from zero to many. So in a burnup report, the term "burn" will raise this green line.

![Report Burnup](pics/burn-up-report.png)

One more report that is commonly used is velocity. Data in the velocity report will come out after the sprint is closed, so we'll skip this for now.

[⬆ Back to top](#top)


## 14 End Sprint
[⬆ Back to top](#top)

At the end of sprint period, a retrospective is usually held, which is evaluation of the sprint that has been running. Jira is not directly linkedto the sprint retrospective, but a sprint in jira itse lf needs to be closed, to move to the next sprint. After closing the sprint, you can also see the velocity report, to evaluate team performance.

### Task
- End the running sprint
- See issues done in previous sprints
- Study the report : Velocity

### Guidance
- Closing a sprint can be done from the Complete Sprint button on the board or backlog screen
- View done issues from the Issue Navigator 

### Solution
You can close sprint from the board menu, or the backlog. click the “Complete Sprint” button. If there are still issues that haven't been resolved then those issues can be moved to a new sprint. 

![Close Sprint](pics/close-sprint-option-1.png)

You can also move it to the product backlog. For example, let's move it to a new sprint. Jira will create a new sprint.

![Close Sprint Move items](pics/close-sprint-move-items.png)

Start the new sprint.

![Start New Sprint](pics/start-new-sprint.png)

You can edit the sprint, and repeat the sprint planning process. What often causes confusion is: how do you see the issues in the previous sprint, which already been done. The screen only displays the product backlog, and sprints that are, or haven't, been running. For issues that have been done, you can see them from the issue navigator. Look for issue which status is "Done".

![Done Items](pics/done-working-items.png)


Now let's take a look at the report, and the velocity report. This velocity shows the result over a sprint, the actual versus plan. Or also called commitment versus actual. The gray one is commitment, user story point that are planned to be completed during the sprint plan. The green is the actual state. Ideally, the green and gray would be the same.

![Velocity Report](pics/velocity-report.png)


[⬆ Back to top](#top)


## 15 Workflow
[⬆ Back to top](#top)

So far, you can change the issue status freely, even for example from todo directly to done. There are times, things like that is not what you need. For example, you want to ensure that all issues must pass the UAT status. Or issues from to do can only be changed to development. This status change is called as transition in the jira, and you can create transition rules as a jira workflow. So the status change rules are defined in the workflow, and you can customize them.

### Task
Modify the workflow so that:
- Status Done can only accept issues whose status is originally from UAT
- Status Development can only accept issues whose status is originally from To Do

### Guidance
To configure workflow, you can select the context menu (...) on the board screen > Manage Workflow

### Solution

From the board click this menu and select “manage workflow”. 

![Manage Workflow](pics/workflow-manage.png)


See here, that the status that is considered complete is the green one. This means that the green status will affect the burndown chart and velocity, because the story point issue will be burned only when it is done. 

![Manage Workflow](pics/workflow-scheme.png)

Gray status means not yet done and blue status means work in progress. Here you can see that any status can be set to done. If you want to ensure, for example, that only issues that have been carried out by the user acceptance test can be done, then you can change this workflow.

Remove the “any status” arrow going to done. This arrow is referred to as a transition n jira. Drag the arrow from UAT or user acceptance test, to Done. Give the transition a name, for example “Finish after UAT”.
![Edit Workflow](pics/edit-workflow.png)


You can also set more rules for example one more, that "development" can only receive from "todo". Save this workflow. 
![Edit Workflow](pics/edit-workflow-2.png)
![Save Workflow](pics/workflow-overview.png)

Now if you return to the board, you can't just move the status to done. You can only move status from UAT to done. 

Likewise, you can only move issues from todo to development according to the workflow that you have just created.

[⬆ Back to top](#top)

## 16 Jira & Slack
[⬆ Back to top](#top)

Slack is an application for communication that is widely used in companies. Although not part of jira or atlassian, slack is very popular. Jira has features for integration with slack, for example when an issue is created or changes status, jira can send messages to slack.

### Taks 
Create a private slack channel, and link your Jira project to that Slack channel. Every time there is a new issue or an issue which status changed to Done, send a notification to the slack channel.

### Guidance
You have to register on https://slack.com/. To connect Jira with slack, you can go to Project Settings > Apps > Slack Integration

### Solution

Go to slack.com and sign up. You can register using gmail or work email. I already have a slack account so I'm going to log in. Then create a slack workspace. The name is up to you. You can use slack via browser, but for convenience I'll download slack and install it on my laptop. Google “download slack” go to this link - https://slack.com/downloads/windows, then download and install slack.

In slack there is channel, some kind of group. Make a channel: mycar. You can create a public or private channel. In private channel, not everyone can enter, only the people you invite.

Make sure that you are logged in to jira and slack with the same email. Then from jira, go to project settings and look for the Slack integration menu.
![Slack Jira Integration](pics/slack-jira.png)

Click the button to connect to slack, then select the slack workspace you want to connect to. Select the channel too, then connect. Then select edit.
![Slack Jira Integration 1](pics/connect-slack-to--jira-1.png)
![Slack Jira Integration 2](pics/connect-slack-to--jira-2.png)
![Slack Jira Integration 3](pics/install-slack-jira.png)


Here you can change the settings, when a message will be sent to the slack channel.

For example let's have a message sent when an issue is created or changes its status to done. Now try to create a new issue from the backlog.

When you create an issue, the message will automatically be sent to the slack channel that you have set.

Likewise if there is an issue which status changes to done. The message will be automatically sent to Slack.

Even better, the message sent is a link that you can click from slack to open the jira issue that changed.

[⬆ Back to top](#top)


## 17 Jira & GitHub
[⬆ Back to top](#top)

Jira also has many apps for integration, both free and paid. In software development, there are tools commonly used for source code management such as github.

Jira has free apps for integration with github. With this integration, software engineers can track on Jira if there are any changes regarding the source code on GitHub. With apps, Jira functionality can be developed, even integration with other software outside of Atlassian products. 

Please understand that this course will not cover GitHub in detail, but will focus on Jira and GitHub integration.

### Taks 
Connect Jira with github repository, so every time a new branch, commit, or pull request is made on github, the issue in Jira will be updated. You must have a github account, and install apps from Jira to connect to github.

### Guidance
Register first on github.

To install apps on Jira, you can go to the Apps menu > Manage Apps. Find an application to connect Jira with Github that is free, then configure the apps.

### Solution
First, you must have a github account as an administrator. Go to github and register.

This course is not about github, so I won't go into details about github. I already have a github account so I'm going to log in.

Create a repository, for example name it “course-jira”. Set as a private repository, so the repository can only be accessed by certain people you invite.

To use apps, you must login with user who create jira project. From jira apps menu, select “manage apps”.

![Manage Apps in Jira](pics/manage-apps-jira.png)


Here you can see all the apps you have. Jira has many apps both free and paid. look at the “Find new apps” section and search for “github”. If you are looking for something free, tick the “free for all teams” option. For jira github integration, you can use this app. Click get app and install.
![GitHub in Jira](pics/jira-github-app.png)

Wait a minute, then if you go to manage apps, you now have github apps. Let's set the app. Make sure you are logged in on github and jira. Then click the connect button in jira. And allow connection between github-jira.

Install if there are requirements or other apps that must be installed on GitHub. In this section you can choose whether you allow access to all repositories or only certain github repositories. Let's try setting only for the course-jira repository. Wait a moment for this process to complete. 

After you finish, try to look at one of the issues. Here there will be a new field related to github : “Development”, where you can track if there is a git branch or commit that matches the issue.

![Work Item GitHub connection in Jira](pics/work-item-github-connection.png)


The method is actually quite easy, all you need is every time you make a git branch or commit make sure there is an issue key, which is this one. 


For example, let's create a new branch in git. In reality, making branches and commits is done by software engineers, and not done from github, but since this course focuses on jira, let's try to make it.

When creating a branch, make sure there is an issue key. Then create a new file and commit.

Make sure when you commit, there is an issue key in the commit title. Then make a pull request from this branch. Back to jira, and now you can see in the related issue, which has the issue key, all the branches, commits, and pull requests are linked and visible, including the status of each one.

So if, for example, the software team merge a pull request the status in Jira will also change. Like this.

You can also create a new branch from Jira. Click this link and you can create a new branch in git.

The rest is for commits and pull requests, the process is the same. Remember: commits and pull requests don't need to be done from github.

It can be from the tools of each software engineer, the important thing is that there is a Jira key when creating branches, making commits or pulling requests.

[⬆ Back to top](#top)


## 18 Bonus & References
[⬆ Back to top](#top)
References
- For sample Jira issue (CSV file), you can download it in this lecture, in the resources section (sample-data-jira.csv)

[⬆ Back to top](#top)



