# Automation-workshop_Session_2
Backend testing  Automation-workshop_Session_2

Todoist API Tests with Postman and Newman.

The tests scenarios covered includes:
- Create a new project
- Get a project
- Update the project name
- Create a new task
- Get an active task
- Get active tasks
- Update a task
- Change a task status to 'complete'
- Reopen a task
- Delete a task
- Create several tasks using a DDT.csv file

## Installation and execution:

Download the project and open the project folder in your favorite IDE.
Once inside, open a new terminal and type *npm i newman -g* to install newman and the reporter *npm i newman-reporter-htmlextra*

To run all the tests type in the terminal:
```
npm run test-several-tasks 
```
This command will initialize all the test, and will create a report.html in the reports folder of the project.
```
npm run test-several-tasks 
```
To run the test that creates several tasks from a csv file
An html report named SeveralTasksReport.html will be created in the reports folder. To visualize the report just open the html file on chrome and enjoy!
