# To-Do List Application

## Overview

This is a simple and elegant web application for managing daily tasks. It allows users to add, complete, and delete tasks, with the task list persisted in the browser's local storage.

## Design and Features

*   **UI/UX:**
    *   A clean, user-friendly interface with a clear input field for adding new tasks.
    *   A prominent "Add" button to submit a new task.
    *   A dynamic list that displays all current tasks.
    *   Interactive tasks that can be marked as "complete" (visually distinguished, e.g., with a line-through).
    *   A "delete" button for each task to permanently remove it from the list.
    *   Responsive design that works seamlessly on both mobile and desktop.
*   **Styling:**
    *   **Colors:** Utilizes a modern and calming color palette using `oklch`.
    *   **Typography:** Clear, readable fonts for easy scanning of tasks.
    *   **Layout:** A centered, single-column layout to focus the user's attention on their tasks.
    *   **Effects:** Subtle shadows and transitions for a polished and premium feel. Interactive elements will have a "glow" effect on hover/focus.
*   **Functionality:**
    *   **Add Task:** Users can type a task into the input field and press Enter or click the "Add" button to add it to their list.
    *   **Complete Task:** Clicking on a task toggles its completion status.
    *   **Delete Task:** Each task has an associated delete button to remove it.
    *   **Persistence:** The application uses the browser's `localStorage` to save the user's tasks, so the list is not lost when the page is reloaded.

## Current Plan

*   **Goal:** Transform the previous Lotto Number Generator into a fully functional To-Do List Application.
*   **Steps:**
    1.  **Modify `index.html`:**
        *   Update the HTML structure to include an input field, an "Add" button, and an unordered list (`<ul>`) to serve as the task container.
    2.  **Modify `style.css`:**
        *   Adapt the existing styles for the new to-do list structure. This includes styling the input, button, and task items, as well as creating styles for the "completed" state.
    3.  **Modify `main.js`:**
        *   Rewrite the JavaScript to implement the to-do list logic. This involves:
            *   Adding an event listener to the form to handle task creation.
            *   Creating functions to render, add, toggle completion, and delete tasks.
            *   Integrating with `localStorage` to load and save the task list.
