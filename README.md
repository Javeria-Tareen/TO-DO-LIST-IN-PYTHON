To-Do List Application
Overview
This project provides two implementations of a To-Do List application:

Console-Based To-Do List: A text-based program with advanced features.
GUI-Based To-Do List: A graphical user interface built using the tkinter library.
Both applications allow you to manage tasks effectively by providing features such as adding, removing, prioritizing, and viewing tasks.

1. Console-Based To-Do List
Features
Add Task: Add tasks with priorities (High, Medium, Low).
Remove Task: Select and delete specific tasks by their number.
Prioritize Task: Change the priority of an existing task.
View Tasks: View all tasks sorted by priority.
Save/Load Tasks: Save tasks to a file (tasks.json) and load them later for persistence.
Clear Tasks: Delete all tasks after confirmation.
Requirements
Python 3.x
JSON module (built-in with Python)
How to Run
Save the code to a file named enhanced-to-do-list.py.
Open a terminal or command prompt.
Run the script using:
bash
Copy code
python enhanced-to-do-list.py
Follow the menu to interact with the application.
Example Usage
plaintext
Copy code
--- To-Do List Manager ---
1. Add Task
2. Remove Task
3. Prioritize Task
4. View Tasks
5. Save Tasks
6. Load Tasks
7. Clear All Tasks
8. Exit
Enter your choice: 1
Enter the task: Finish Python project
Enter priority (1=High, 2=Medium, 3=Low): 1
Task 'Finish Python project' added successfully!


2. GUI-Based To-Do List
Features
Add Task: Input tasks and select a priority level using a dropdown.
Delete Task: Select a task from the list and delete it.
View Tasks: Tasks are displayed in a listbox, sorted by priority.
Save/Load Tasks: Save tasks to a file (tasks.json) and load them later for persistence.
Clear All Tasks: Clear all tasks from the list.
Requirements
Python 3.x
tkinter module (built-in with Python)
JSON module (built-in with Python)
How to Run
Save the code to a file named todo_gui.py.
Open a terminal or command prompt.
Run the script using:
bash
Copy code
python to-do-list-with-gui.py
Use the GUI interface to interact with the application.
