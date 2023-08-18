# PriorityWise

PriorityWise is a web application built with React for managing tasks. It allows users to create, update, and delete tasks, as well as move tasks between different statuses such as Backlog, In Progress, and Done.

## Features

- **Status-based Task Management**: Tasks are organized into different status lines such as Backlog, In Progress, and Done. Users can add new tasks to each status line, update task details, and move tasks between status lines.
- **Task Details**: Each task includes a title, description, and urgency level. Users can edit the task details, including the title, description, and urgency level (low, medium, or high).
- **Task Actions**: Users can perform actions on tasks such as saving changes, deleting tasks, and moving tasks between different status lines.
- **Local Storage**: Task data is stored in the browser's local storage, allowing tasks to persist across page reloads.

## Installation

1. Clone the repository: `git clone https://github.com/AvikNayak22/task-manager-react.git`.
2. Navigate to the project directory: `cd task-manager-react`.
3. Install the dependencies: `npm install`.
4. Start the development server: `npm run dev`.

## Usage

1. Upon opening the application, you will see three status lines: Backlog, In Progress, and Done.
2. To add a new task, click the "+" button on the respective status line. This will create an empty task that you can edit.
3. To edit a task, click on the task to expand it and make changes to the title, description, and urgency level.
4. To save changes to a task, click the "Save" button. If the task was collapsed, it will be collapsed again.
5. To delete a task, click the "X" button on the collapsed task.
6. To move a task between status lines, click the left or right arrow buttons on the task.

## Contributing

Contributions to the Task Manager project are welcome and encouraged! If you have any improvements or bug fixes, feel free to submit a pull request.
