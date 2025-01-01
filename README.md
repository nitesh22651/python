# To-Do List Program

This code defines a Task_Manager class that implements a console-based to-do list application. The program allows users to:

Add Task: Add new tasks to the list.
View Tasks: Display all tasks along with their completion status (Done/Not Done).
Mark Task as Complete: Update the status of a task to "Done."
Delete Task: Remove a task from the list.
Exit: Exit the application..


# Team Members
1) **Nitesh Sonawane**
2) **Krushna Khillari**
3) **Ajinkya Khose**
4) **Manish Patil**


## Requirements

- Python 3.x

## How to Use

1. Clone or download this repository to your local machine.
2. Open a terminal or command prompt.
3. Run the `todo_list.py` script using the command:
   ```
   python todo_list.py
   ```
4. Follow the prompts in the console to interact with the program.

## Program Flow

1. The program displays a menu with five options:
    - Add Task
    - View Tasks
    - Mark Task as Complete
    - Delete Task
    - Exit

2. Based on your input, the program performs the corresponding action:
    - **Add Task**: Prompts you to enter a task and adds it to the list.
    - **View Tasks**: Displays all tasks along with their completion status.
    - **Mark Task as Complete**: Prompts for a task number to mark as done.
    - **Delete Task**: Prompts for a task number to delete.
    - **Exit**: Exits the application.

3. Invalid inputs or choices are handled with appropriate error messages.

## Example Usage

```text
To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 1
Enter a task: Buy groceries
Task added!

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 2

Tasks:
1. Buy groceries - Not Done

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 3
Enter task number to mark as complete: 1
Task marked as complete!

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 2

Tasks:
1. Buy groceries - Done
```

## Author
This program was created as an example of a simple console-based to-do list application in Python.

## License
This project is open-source and free to use. No license required.
