# Take-home Assignment

## Overview
You are tasked to build a kanban board on a web application for the development team to manage their development tasks. The kanban board consists of 4 main columns, Backlog, To Do, Ongoing and Done.

User Stories for Kanban Board Web Application

| Story                                                                                     | Acceptance Criteria                                                                                                                                                                                                                                                                                                                                                                                    | Required |
|-------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|
| 1. As a user, I am able to log into the application.                                         | User is able to input his username and password into the input field on the login page.<br><br>User is able to be directed into the kanban board page upon successful login when clicking the submit button.<br><br>User is able to see error message upon unsuccessful login when clicking the submit button.                                                                                                     | Yes      |
| 2. As a user, I am able to create a new task and the new task will be shown in the backlog   | Given the user is logged in successfully, when the user inputs into 'new task name' field and click create. Then the user should see the task created in the backlog column                                                                                                                                                                                                                            | Yes      |
| 3. As a user, I am able to remove a task from any of the kanban board column                 | Given the user clicks on any task in one of the four column, the task name will be shown in a read-only input field.<br><br>Given the task name is shown in a read-only input field and the user clicks on delete button, then the user should see the task is removed from the column.                                                                                                                      | Yes      |
| 4. As a user, I am able to move a task forward to the next column in the kanban board.       | Given the user clicks on any task in one of the four column, the task name will be shown in a read-only input field.<br><br>Given the task name is shown in a read-only input field and the user clicks on a 'Move forward' button, then the task will be moved to the next column.<br><br>Given the user clicks on a task in the Done (last) column, then the move forward button will be disabled.               | Yes      |
| 5. As a user, I am able to move a task backwards to the previous column in the kanban board. | Given the user clicks on any task in one of the four column, the task name will be shown in a read-only input field.<br><br>Given the task name is shown in a read-only input field and the user clicks on a 'Move backwards' button, then the task will be moved to the previous column.<br><br>Given the user clicks on a task in the Backlog (first) column, then the 'Move backwards' button will be disabled. | Yes      |


Wireframe (User story 2: Creating a task)
![Alt Text](https://github.com/ashdevcore/interview-assignment/blob/master/new_task.gif)


Wireframe (User story 3: Deleting a task)
![Alt Text](https://github.com/ashdevcore/interview-assignment/blob/master/delete_task.gif)


Wireframe (User story 4: Move a task forward)
![Alt Text](https://github.com/ashdevcore/interview-assignment/blob/master/moveforward.gif)

Wireframe (User story 5: Move a task backwards)
![Alt Text](https://github.com/ashdevcore/interview-assignment/blob/master/movebackward.gif)


### Front-end tasks and requirements

- Build the application in any framework/libraries of your choice (Preferably ReactJS or VueJS but others are also welcome)
- You are free to mock the data required to develop this application, including login.
- Feel free to use any third party libraries or starter projects.  Choice of third party libraries will also be part of the evaluation.
- Bonus (Optional): 
  - Use any testing libraries or framework to test against the acceptance criteria defined in the user stories.
- Timeline of the assignment is 3 days, please let us know if you need time extension.
