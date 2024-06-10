# CRUD Application With Express and HTMX
Creating a CRUD(Create, Read, Update, Delete) application is a great way to understand the basics of web development. By the end of this tutorial, you'll have a working application that allows you to add, view, edit and delete tasks. Let's get coding! 😸

# Screenshot
![](https://github.com/PaladinKnightMaster/crud-htmx-express/blob/main/public/assets/screenshot.png)

# API

* GET /api/todos: This route returns the list of todos
* POST /api/todos: This route adds a new todo to the list
* PUT /api/todos/🆔 Updates an existing todo based on the provided ID
* DELETE /api/todos/🆔 Deletes a todo based on the provided ID

# Running the Application
To run the application, open your terminal and navigate to the project directory. Start the server with the following command:
```
node src/server.js
```
Open your browser and navigate to "http://localhost:3000". You should see your CRUD application running. You can add, edit and delete tasks, and the changes will be reflected without reloading the page.