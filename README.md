# Todo List Application

A simple and interactive Todo List application built using **React**. This app allows users to manage their tasks by adding new todos, editing, marking them as complete, and deleting tasks. The tasks are stored locally in the browser using **localStorage** to persist them even after refreshing the page.

## Features:
- **Add tasks** with a title and description.
- **Edit tasks** by updating the title and description.
- **Mark tasks as completed** and move them to a completed list.
- **Delete tasks** from both the active and completed lists.
- Data is persisted using **localStorage** to retain tasks after page reloads.

## Table of Contents:
1. [Setup Instructions](#setup-instructions)
2. [How to Run the Project](#how-to-run-the-project)
3. [Technologies Used](#technologies-used)
4. [Additional Notes](#additional-notes)

## Setup Instructions

1. Clone the repository:

To get started, first clone the repository to your local machine:

2. Install Dependencies:
Once inside the project directory, install the required dependencies using npm:
cd todo-app
npm install

3. Start the Development Server:
After installing the dependencies, start the development server to run the app locally:
npm start

This will open the app in your default web browser at http://localhost:3000.

How to Run the Project
After completing the setup, follow these steps to run the project:

Navigate to the project directory in your terminal.

Run the following command to start the development server:
npm start

The app will open automatically in your default browser at http://localhost:3000.
Running Tests
To run tests for the application, use the following command:
npm test


This will run all the test cases and display the results in the terminal.

Technologies Used
React: For building the user interface components.
React Router (if added): For managing different views or pages.
CSS: For styling the application.
localStorage: For persisting tasks data across page reloads.
React Icons: For adding interactive icons to the UI.

Additional Notes
localStorage is used to store tasks data, which means the tasks will remain in the app even after you refresh the page.
The application allows toggling between two views: Todo (incomplete tasks) and Completed (tasks that are finished).
The app is responsive and works well on both desktop and mobile devices.





