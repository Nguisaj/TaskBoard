This is a simple Task board project built using HTML, CSS powered by jQuery, and  JavaScript. It allows you to create tasks and organize them into different stages, add individual project tasks, manage their
state of progress and track overall project progress accordingly.

Features
GIVEN a task board to manage a project
WHEN I open the task board
THEN the list of project tasks is displayed in columns representing
the task progress state (Not Yet Started, In Progress, Completed)
WHEN I view the task board for the project
THEN each task is color coded to indicate whether it is nearing the
deadline (yellow) or is overdue (red)
WHEN I click on the button to define a new task
THEN I can enter the title, description and deadline date for the
 new task into a modal dialog
WHEN I click the save button for that task
THEN the properties for that task are saved in localStorage
WHEN I drag a task to a different progress column
THEN the task's progress state is updated accordingly and will stay
in the new column after refreshing
WHEN I click the delete button for a task
THEN the task is removed from the task board and will not be
added back after refreshing
WHEN I refresh the page
THEN the saved tasks persist
Drag and drop tasks between different stages of the board
Create new tasks and assign them to a stage
Edit task details
Delete tasks from the board
Responsive design for mobile and desktop devices

Technologies Used
HTML
CSS
JavaScript
Drag and Drop API
Getting Started
To get started with the Kanban board, follow these steps:

Clone the repository: git clone https://github.com/Nguisaj/TaskBoard
Open the project in your preferred code editor.
Open the index.html file in your web browser.
Usage
Once you have the project running, you can perform the following actions:

To create a new task, click on the "Add Item" button and fill in the required details.
To move a task to a different stage, simply drag and drop it to the desired column.
To edit a task, click on the task card and update the details.
To delete a task, click on the task card and delete the details.
