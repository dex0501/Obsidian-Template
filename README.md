Obsidian reference vault with all needed plugins and customizations.

## Summary
Main view
![](./__attachments__/homepage.png)

### File Structure
- "__attachments__" -> Every folder has its own folder for attachments.
- "Homepage.md" -> Main page. This opens at boot.
- "__Tasks" -> All tasks goes here (try to use shortcut Alt + T).
- "__Templates" -> All templates are here.
- "__Unsorted" -> If you create new file and it is not set in the folder, it will be here.
- "Private" -> Private files
- "Private" -> Work related files (projects, people, meetings,...)
- "Learning" -> Learning materials and goals

```tree.txt
├── Homepage.md
├── .obsidian
├── __attachments__
├── __Tasks
│   ├── Ideas.md
│   └── Tasks.md
├── __Templates
│   ├── Company Role Template.md
│   ├── Company Template.md
│   ├── Diary Template.md
│   ├── Location Template.md
│   ├── Meetings
│   │   ├── 1on1 Meeting Template.md
│   │   ├── Problem Solving Meeting Template.md
│   │   └── Standard Meeting Template.md
│   ├── Person Template.md
│   └── Project Template.md
├── __Unsorted
│   └── __attachments__
├── Learning
├── Private
└── Work
    ├── Companies
    │   └── Boring Company.md
    ├── Company Roles
    │   ├── Role_QA.md
    │   └── Role_Software_Developer.md
    ├── Idea Dump.md
    ├── Locations
    │   └── Work Office.md
    ├── People
    │   ├── Person A.md
    │   └── Person B.md
    └── Projects
        └── Secret_Project
            ├── Meeting
            │   └── MoM 20230301.md
            └── Secret_Project.md
```


## Quick Start Guide

### Generate a diary (daily note) for today.
1. `CTRL + P`
2. Type: `new day`   (QuickAdd plugin)
3. Diary note for today will be created in the folder `Diary` with name `Diary-yyyymmdd`
4. You can access specific diary by clicking on the specific date in the calendar (upper-right corne)   
![](__attachments__/new_day.png)
### Add new log
1. `ALT + L`
2. Write the message (you should include the person)
   ![[Pasted image 20230319165420.png]]
3. This message will occur in the diary create in the first step in the log section.
4. Also, it will be placed in the log section of the mentioned person. 
   ![](person_look.png)
### Add new task
1. `ATL + T` or command  `new task`
2. Set reminder.
	  ![](reminder.png)
3. Set due date.
	  ![](duedate.png)
4. Set the task.
	  ![](task_name.png)
5. Set the task priority.
	  ![](set_prior.png)
6. The task is written in the `__Tasks/Tasks.md`   (NOTE: If you want create the task in the current file use command `new task here`)
	  ![](task_look.png)
8. It is also visible inside the today's diary.
9. If you set up the Card Board it will be visible there. 
	
## Features

### List of plugins 

### List of templates


## Shortcuts



