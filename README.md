# Todo-List Angular Application

## Overview
This is a simple Todo-List web application built with Angular that allows users to create, view, edit, and delete tasks. The app uses a JSON file as an initial data source and manages tasks in memory during runtime.

## Screenshots

### 📝 Task List View
![Task List](./screenshots/Capture.png) 

### ➕ Add New Task
![Add Task](./screenshots/2.png) 

### ✏️ Delete Task 
![Delete Task](./screenshots/del.png) 

## Features
- Display a list of tasks with title and notes.
- Add new tasks with a title and note.
- Edit existing tasks.
- View details of a specific task.
- Delete tasks.
- Uses reactive forms for input handling.
- Basic navigation between views.

## Project Structure
- `src/app`: Contains Angular components and services.
  - `task-storage.service.ts` — Manages task data and operations.
  - Components:
    - `TaskAddComponent` — Form to add new tasks.
    - `TaskEditComponent` — Edit task details.
    - `TaskViewComponent` — View and delete tasks.
    - `TodoComponent` — Displays the list of tasks.
- `src/assets/todo-list.json`: Initial tasks data loaded on app start.
- `task.model.ts`: Defines the Task class.

## Getting Started

### Prerequisites
- Node.js (v14+ recommended)
- Angular CLI

```bash
npm install -g @angular/cli

