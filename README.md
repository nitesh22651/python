# Task-Planner Program

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
- VS code editor or
- Command prompt

## How to Run

1. Open a terminal or command prompt.
2. Run the `todo_list.py` file using the command:
   ```
   python todo_list.py
   ```
3. Follow the prompts in the console to interact with the program.

## Program Flow

1. The program displays a menu with five options:
    - Add Task
    - View Tasks
    - Mark Task as Complete
    - Delete Task
    - Exit

2. Based on your input, the program performs the corresponding action:
    - **Add Task**: Allows you to enter a task and adds it to the list.
    - **View Tasks**: Displays all tasks along with their completion status.
    - **Mark Task as Complete**: Allows for a task number to mark as done.
    - **Delete Task**: Allows for a task number to delete.
    - **Exit**: Exits the application.

3. Invalid inputs or choices are handled with appropriate error messages.

## Example Usage

```text
PS C:\Users\sonaw\OneDrive\Desktop> python todopython.py

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 1
Enter a task: assignment completion
Task added!

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 1
Enter a task: project work
Task added!

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 1
Enter a task: running or gym
Task added!

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 2

Tasks:
1. assignment completion - Not Done
2. project work - Not Done
3. running or gym - Not Done

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 3
Enter task number to mark as complete: 3
Task marked as complete!

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 2

Tasks:
1. assignment completion - Not Done
2. project work - Not Done
3. running or gym - Done

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 4
Enter task number to delete: 3
Task 'running or gym' deleted!

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 2

Tasks:
1. assignment completion - Not Done
2. project work - Not Done

To-Do List:
1. Add task
2. View tasks
3. Mark task as complete
4. Delete task
5. Exit
Enter your choice: 5
Goodbye!
PS C:\Users\sonaw\OneDrive\Desktop>
```


