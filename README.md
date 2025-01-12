# Todo App

A simple **Todo Application** built using HTML, CSS, and JavaScript. This project demonstrates how to create a basic to-do list with features like adding, editing, deleting, and persisting tasks using **localStorage**.

---

## Features

- **Add Tasks**: Users can add new tasks to the list by entering text and clicking the "Add" button.
- **Edit Tasks**: Users can click the edit button to update an existing task.
- **Delete Tasks**: Tasks can be removed from the list by clicking the delete button.
- **Persistent Data**: All data is stored using `localStorage`, allowing the to-do list to persist even after refreshing the page.
- **Responsive Design**: The app is visually optimized for both desktop and mobile screens using CSS media queries.

---

## Project Structure and Implementation

### 1. **HTML for Structure**:
   - The app features a header for inputting tasks and a main section displaying the list of tasks.
   - Buttons for editing and deleting individual tasks use Font Awesome icons for a better visual experience.

### 2. **CSS for Styling**:
   - The design is simple, clean, and responsive.
   - A mix of custom fonts (`Press Start 2P` and `Inter`) and airy layouts make the app visually appealing.

### 3. **JavaScript for Functionality**:
   - **Dynamic UI Rendering**: 
     - Tasks are dynamically displayed based on the data in `todolist`.
   - **Event Handling**:
     - Click events are attached to add, edit, and delete buttons to manage tasks.
   - **Local Storage Integration**:
     - Tasks are stored in `localStorage` for persistence between sessions.
   - **Core JavaScript Functions**:
     - `addToDo()`: Adds a new task.
     - `editTodo()`: Edits an existing task.
     - `deleteTodo()`: Deletes a specific task.
     - `printUI()`: Updates the UI after any changes.
     - `saveData()`: Stores the current state of the `todolist` in `localStorage`.

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project folder:
   ```bash
   cd <project-folder>
   ```
3. Open the `index.html` file in your favorite browser:
   - No additional dependencies are required, as the project uses pure HTML, CSS, and JavaScript.

---

## Future Enhancements

- Add task completion (checkmark) functionality.
- Categorize tasks (e.g., Work, Personal).
- Sort tasks based on priority or due dates.
- Introduce APIs for backend integration to support multiple users.

---
