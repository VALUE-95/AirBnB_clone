# AirBnB Clone

## Description
The AirBnB Clone project aims to create a simplified version of the AirBnB platform. It involves building a command-line interface (CLI) to manage AirBnB objects such as users, listings, bookings, and more. The project utilizes Python and Object-Oriented Programming (OOP) principles to implement various functionalities.

## Command Interpreter
The command interpreter serves as the main interface for interacting with the AirBnB objects. It allows users to perform operations like creating, retrieving, updating, and deleting objects, as well as executing various commands for managing the application.

### How to Start
To start the command interpreter, follow these steps:
1. Clone the AirBnB Clone repository from GitHub.
2. Navigate to the project directory.
3. Run the console.py script using Python.

```bash
$ ./console.py
```

### How to Use
Once the command interpreter is running, you can use various commands to interact with the AirBnB objects. Here are some basic commands:

- `create <class>`: Create a new instance of the specified class.
- `show <class> <id>`: Show details of a specific instance.
- `update <class> <id> <attribute> <value>`: Update the attribute of a specific instance.
- `destroy <class> <id>`: Delete a specific instance.
- `all <class>`: Show all instances of a specific class.
- `quit`: Exit the command interpreter.

### Examples
```bash
$ ./console.py
(hbnb) create User
2fbc17b8-4a2d-11ec-8898-080027a63154
(hbnb) show User 2fbc17b8-4a2d-11ec-8898-080027a63154
[User] (2fbc17b8-4a2d-11ec-8898-080027a63154) {'id': '2fbc17b8-4a2d-11ec-8898-080027a63154', 'created_at': '2024-02-12T12:00:00', 'updated_at': '2024-02-12T12:00:00'}
(hbnb) update User 2fbc17b8-4a2d-11ec-8898-080027a63154 name John
(hbnb) show User 2fbc17b8-4a2d-11ec-8898-080027a63154
[User] (2fbc17b8-4a2d-11ec-8898-080027a63154) {'id': '2fbc17b8-4a2d-11ec-8898-080027a63154', 'created_at': '2024-02-12T12:00:00', 'updated_at': '2024-02-12T12:01:00', 'name': 'John'}
(hbnb) quit
$
```

## Authors
- Tarek Hamdoudi
- Victor Ochuba

Make sure to replace the placeholders with actual information relevant to your project.
