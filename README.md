# Todo-In-CLI
Todo-In-CLI is a command-line application that helps you manage your tasks and users efficiently. It provides a simple and convenient way to create, read, update, and delete tasks, as well as manage user sessions. Keep track of your todos and stay organized with this easy-to-use CLI tool.
## Installation

To use Todo-In-CLI, you need to have Node.js installed on your system. If you haven't already, you can download it from [Node.js official website](https://nodejs.org/).
You also need to have a mongodb server to persist data.

1. Clone this repository:
   git clone https://github.com/Temitopesam1/Todo-In-CLI.git
2. Change to the project directory:
   cd Todo-In-CLI
3. Install the necessary dependencies:
   npm i -g .

#Make sure you have in the root folder a .env file that contains your mongoDB connection string.

## Usage

The Todo-In-CLI app provides the following commands:

### add

Create a new todo task.

Usage: todo add

### addUser

Create a new user.

Usage: todo addUser

### user

Retrieve a list of all users.

Usage: todo user

### deleteUser

Delete a user by their ID.

Usage: todo  deleteUser

### login

Create a new session.

Usage: todo login

### logout

End the current session.

Usage: todo logout

### read

Read and display all todo tasks.

Usage: todo read

### update

Update a todo task by its ID.

Usage: todo update

### delete

Delete a todo task by its ID.

Usage: todo delete

### help [command]

Display help information for a specific command or a list of available commands.

Usage: todo help


## Contributing

Feel free to contribute to this project by opening issues or creating pull requests on GitHub.

## License

This project is licensed under the MIT License
