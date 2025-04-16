# CSS3 Transitions, Animations, and Advanced JavaScript Functions

## Objectives

Create smooth CSS transitions and animations.
Use JavaScript functions for dynamic behavior.
Implement local storage for data persistence.

## Instructions
Add CSS animations to elements like buttons or images.

>[!NOTE]
> - Write a JavaScript function that:
> - Stores and retrieves user preferences using localStorage.
> - Implements an animation triggered by user actions.

## Tasks

Create a CSS animation.
Store data in localStorage.
Apply JavaScript to trigger animations.

# Task Manager Webpage

## Overview
This project is a dynamic and interactive **Task Manager** webpage built to demonstrate CSS3 transitions and animations, JavaScript functions, and localStorage for data persistence. It allows users to add, view, and delete tasks with a modern, user-friendly interface. The webpage features smooth animations, transitions, and persistent task storage, making it a practical tool for managing to-do lists.

## Features
- **CSS Animations and Transitions**:
  - Smooth hover effects on the "Add Task" button (scale and color change).
  - Pulse animation when clicking the "Add Task" button.
  - Fade-in animation for newly added tasks.
  - Fade-out and slide transition when deleting tasks.
  - Border color transition on the input field when focused.
- **JavaScript Interactivity**:
  - Add tasks via button click or Enter key.
  - Delete tasks with a smooth animation.
  - Render tasks dynamically from localStorage on page load.
- **LocalStorage**:
  - Tasks are saved persistently in the browser's localStorage.
  - Tasks are retrieved and displayed on page load.
- **Responsive Design**:
  - Clean, centered layout optimized for both desktop and mobile devices.
  - Task list has a maximum width for readability.

## Technologies Used
- **HTML5**: Structure of the webpage.
- **CSS3**: Styling, transitions, and animations (e.g., keyframes for fade-in and pulse effects).
- **JavaScript**: Dynamic behavior, event handling, and localStorage management.
- **LocalStorage**: Browser API for persistent task storage.

## Setup and Running
1. **Clone or Download**:
   - Copy the `index.html` file from this project to your local machine.
2. **Run the Webpage**:
   - Open `index.html` in a modern web browser (e.g., Chrome, Firefox, Edge).
   - No additional setup or server is required as it runs entirely in the browser.
3. **Interact with the Task Manager**:
   - **Add a Task**: Type a task in the input field and click "Add Task" or press Enter.
   - **View Tasks**: Tasks appear in a list with a fade-in animation.
   - **Delete a Task**: Click the "Delete" button next to a task to remove it with a fade-out effect.
   - **Persist Tasks**: Refresh the page to verify tasks are saved and reloaded from localStorage.

## File Structure
- `index.html`: The main (and only) file containing HTML, CSS, and JavaScript for the Task Manager.

## Usage
- **Adding Tasks**:
  - Enter a task in the input field (e.g., "Buy groceries").
  - Click the "Add Task" button or press Enter.
  - The task appears in the list with a fade-in animation.
- **Deleting Tasks**:
  - Click the "Delete" button next to a task.
  - The task fades out and slides before being removed.
- **Hover Effects**:
  - Hover over the "Add Task" button to see it scale and change color.
- **Persistent Storage**:
  - Tasks are automatically saved to localStorage.
  - Reloading the page retains all tasks.

## Notes
- The webpage is fully client-side and does not require a backend or external dependencies.
- Tasks are stored in localStorage as a JSON array, with each task having a unique ID (based on timestamp) and text content.
- The design prioritizes simplicity and usability, with animations enhancing the user experience without overwhelming it.

## Future Improvements
- Add task categories or priorities.
- Implement task editing functionality.
- Include a "Clear All Tasks" button.
- Enhance styling with a CSS framework (e.g., Tailwind CSS) for more customization.

## License
This project is open-source and available for educational purposes. Feel free to modify and distribute as needed.

## Acknowledgments
Built as part of an assignment to showcase CSS3 animations, JavaScript interactivity, and localStorage usage in a practical context.

Happy Task Managing! 💻✨
