Todo-List Angular Application
Overview
This is a simple Todo-List web application built with Angular that allows users to create, view, edit, and delete tasks. The app uses a JSON file as an initial data source and manages tasks in memory during runtime.

Features
Display a list of tasks with title and notes.

Add new tasks with a title and note.

Edit existing tasks.

View details of a specific task.

Delete tasks.

Uses reactive forms for input handling.

Basic navigation between views.

Project Structure
src/app: Contains Angular components and services.

task-storage.service.ts — Manages task data and operations.

Components:

TaskAddComponent — Form to add new tasks.

TaskEditComponent — Edit task details.

TaskViewComponent — View and delete tasks.

TodoComponent — Displays the list of tasks (assumed).

src/assets/todo-list.json: Initial tasks data loaded on app start.

task.model.ts: Defines the Task class.

Getting Started
Prerequisites
Node.js (v14+ recommended)

Angular CLI (npm install -g @angular/cli)

Installation
Clone the repository:

bash
Copy
Edit
git clone <repo-url>
cd todo-list-master
Install dependencies:

bash
Copy
Edit
npm install
If you face JSON import issues, ensure tsconfig.json includes:

json
Copy
Edit
{
  "compilerOptions": {
    "resolveJsonModule": true,
    "esModuleInterop": true,
    ...
  }
}
Running the Application
Start the development server:

bash
Copy
Edit
ng serve
Open your browser and go to:

arduino
Copy
Edit
http://localhost:4200
Usage
Navigate to Tasks to view the list.

Use Add Task to create a new task.

Click on a task to view or edit its details.

Use the delete option to remove a task.

Testing
Basic unit tests are provided for the root component. Run tests with:

bash
Copy
Edit
ng test
Future Improvements
Add data validation on forms.

Persist tasks in local storage or backend.

Enhance UI/UX with better styling.

Implement user authentication.

Add comprehensive unit and integration tests.

