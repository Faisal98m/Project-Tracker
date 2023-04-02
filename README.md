# Project-Tracker

This is a simple project time tracker that allows you to enter project details and displays them on a table. The application is built with JavaScript and utilizes the Moment.js library for date/time handling and the jQuery library for DOM manipulation.

Usage
When the page loads, the current date and time are displayed at the top of the page. To add a new project, click the "Add Project" button and fill out the form with the project details, including the project name, type, hourly rate, and due date. Once you submit the form, the project data will be displayed on the table below.

Each project is displayed in a table row with columns for the project name, type, hourly rate, due date, days left, total earnings, and a delete button. You can delete a project by clicking the delete button for that row.

Functionality
The application includes several functions for handling the display of time, adding and deleting projects, and calculating the total earnings for a project based on the hourly rate and days left until the due date.

The application also utilizes the jQuery UI Datepicker widget to allow for easy selection of a due date.

Dependencies
Moment.js
jQuery
jQuery UI
