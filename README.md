# To-Do List Application

## Overview
The To-Do List Application is a simple web-based tool designed to help users organize and manage their tasks efficiently. It provides an intuitive interface for adding, marking, and deleting tasks, and it automatically saves your task list using local storage for persistent access.

## Features
- **Add Tasks:** Quickly add tasks using the input box and "Add" button.
- **Mark as Completed:** Click on a task to toggle its "completed" status (crossed out).
- **Delete Tasks:** Remove tasks by clicking the delete (×) button next to each task.
- **Persistent Data:** Tasks are stored in the browser's local storage and loaded automatically when the application is reopened.

## Technologies Used
- **HTML:** For structuring the application.
- **CSS:** For styling the application with a modern and clean design.
- **JavaScript:** For interactivity and managing tasks.

## Files
1. **todolist.html:** The main HTML file containing the structure of the application.
2. **todolist.css:** The CSS file for styling the application.
3. **todolist.js:** The JavaScript file implementing the functionality of the To-Do List.

## Installation and Usage
1. **Download the Project:**
   Download all files (HTML, CSS, and JS) and ensure they are in the same directory.
2. **Run the Application:**
   Open `todolist.html` in any modern web browser.
3. **Start Managing Tasks:**
   - Enter a task in the input box and click the "Add" button.
   - Click on tasks to mark them as completed.
   - Click the delete (×) icon to remove tasks.

## How It Works
1. **Adding a Task:**
   - When a task is added, it is displayed as a list item in the task list.
   - Tasks can have a delete button (×) appended for removal.
2. **Marking as Completed:**
   - Clicking on a task toggles a `checked` CSS class, visually distinguishing completed tasks with a strike-through effect.
3. **Deleting Tasks:**
   - Clicking the delete button (×) removes the corresponding task.
4. **Saving and Loading Data:**
   - The `saveData` function saves the current task list in local storage.
   - The `showData` function retrieves and displays tasks when the application is reloaded.

## Preview
![To-Do List Preview](placeholder-for-screenshot)

## Customization
You can easily modify the styling in `todolist.css` or extend the functionality in `todolist.js` to meet specific needs, such as categorizing tasks or adding deadlines.

## License
This project is free to use under the [MIT License](https://opensource.org/licenses/MIT).

## Contributions
Contributions are welcome! Feel free to fork this repository, make improvements, and submit pull requests.
