# CRUD Application With Express and HTMX

Creating a CRUD (Create, Read, Update, Delete) application is a great way to understand the basics of web development. By the end of this tutorial, you'll have a working application that allows you to add, view, edit, and delete tasks. Let's get coding! 😸

## Screenshot
![Application Screenshot](https://github.com/PaladinKnightMaster/crud-htmx-express/blob/main/public/assets/screenshot.png)

## Features

- Add new tasks
- View existing tasks
- Edit tasks
- Delete tasks
- Dynamic updates without page reload using HTMX

## API

* `GET /api/todos`: Returns the list of todos
* `POST /api/todos`: Adds a new todo to the list
* `PUT /api/todos/:id`: Updates an existing todo based on the provided ID
* `DELETE /api/todos/:id`: Deletes a todo based on the provided ID

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/PaladinKnightMaster/crud-htmx-express.git
    cd crud-htmx-express
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

## Running the Application

To run the application, open your terminal and navigate to the project directory. Start the server with the following command:

```bash
node src/server.js
```
Open your browser and navigate to http://localhost:3000. You should see your CRUD application running. You can add, edit, and delete tasks, and the changes will be reflected without reloading the page.

## Project Structure

```bash
crud-htmx-express/
├── public/
│   ├── assets/
│   └── ...
├── src/
│   ├── server.js
│   └── ...
├── .gitignore
├── package.json
├── package-lock.json
└── Readme.md
```
* **public/**: Contains static assets such as images, CSS, and client-side JavaScript.
* **src/**: Contains the server-side code.
* **.gitignore**: Specifies files and directories to be ignored by Git.
* **package.json**: Lists the project dependencies and scripts.
* **package-lock.json**: Records the exact versions of dependencies installed.
* **Readme.md**: Project documentation.

## Dependencies

- Express
- HTMX

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.