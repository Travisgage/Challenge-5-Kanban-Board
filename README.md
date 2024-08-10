# Task-Board

## Description

The following is a kanban board application that allows users to organize tasks into three categories (to do, in progress, and done) and move them through each category's column to help productivity by clarifiying workflow for individuals or groups.  The application includes visual feedback for the user by coloring task cards that may be a higher priority according to their due dates -- white as a default card color, yellow for tasks due on the same day, and red for past due items. Finally, the user can delete tasks that have been completed and no longer need to be tracked on the board.

## Installation

N/A

## Usage

To get started with the kanban board, navigate to the application URL in your browser.  The user can add tasks to the workflow by clicking the 'add task' button and entering a title, selecting a due date on the date picker calendar interface, and providing a description of the task.  The newly created task will then be displayed as a card in the "to-do" colunn by default.  From here, users may continue to add tasks and move them through their workflow by clicking and dragging task cards between the 'in-progress' and 'completed' columns. In the event that a specific task is due the same day the application is being used, it will be displayed with a yellow background. Past due tasks will display with a red background. Any task cards dragged into the 'completed' column will again display as the default white, independent of their respective due dates.  Local storage is used so that data will persist following page refresh, preserving whatever tasks the user had on the board.  Following completion, tasks cards may be deleted from the board using the 'delete' button at the bottom of the card.     

Click [here](https://travisgage.github.io/Challenge-5-Kanban-Board/) to view deployed application.

![Screenshot of application](./assets/images/task%20board%20screenshot.png)

## Credits

Bootstrap, Jquery, dayjs, and Jquery UI.

## License

N/A

