# To-Do List Program

## Description
The To-Do List project is a Python-based application that helps users organize and manage their tasks. It provides an interactive interface where users can add tasks, view a list of tasks, mark tasks as complete, delete tasks, and exit the program. The application is designed for simplicity and ease of use, making task management straightforward and efficient.


## Team Members
1) **Nitesh Sonawane**
2) **Krushna Khillari**
3) **Ajinkya Khose**
4) **Manish Patil**

## Phases of project

**Phase 1: Planning and Requirements**
* Objective: Define the purpose and scope of the project.
* Tasks :
  1) Identify key features: Add tasks, view tasks, mark tasks as complete, delete tasks, and exit.
  2) Decide on the programming language and tools (e.g., Python).
     
**Phase 2: Basic Implementation**
* Objective: Develop the core functionality of the To-Do List.
* Tasks:
   - Set up a Python class (Task_Manager) and initialize the todo_list method.
   - Add tasks.
   - View tasks in a numbered list with status (Done/Not Done).
   - Mark tasks as complete.
   - Delete tasks by number.
   - Provide an exit option to close the application.
   - Add input prompts and print statements for user interaction.

**Phase 3: Code Optimization**
* Objective: Refactor code for better readability and maintainability.
* Tasks:
  * Modularize the code by separating each action into individual methods:
      - add_task(), view_tasks(), mark_task_complete(), delete_task().
      - Reuse the view_tasks() method in relevant places.
      - Use comments to explain the logic.

**Phase 4: Testing and Debugging**
* Objective: Ensure the application works as expected.
* Tasks:
   - Test each feature with various inputs and edge cases.
   - Fix bugs and unexpected behaviors.
   - Conduct usability testing with other users for feedback.

## Requirements

- Python 3.x,
- VS code editor

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
