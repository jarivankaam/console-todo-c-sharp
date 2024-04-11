To-Do List Application
======================

Overview
--------

This is a simple command-line application that allows users to add, remove, and mark tasks as complete. The list
of tasks is displayed on the console when the user runs the application.

Features
--------

* Add Task: Users can add new tasks by entering them in the command line using the following format: `AddTask
{task name}`. For example, `AddTask Grocery Shopping` would add a task named "Grocery Shopping" to the list.
* Remove Task: Users can remove tasks from the list by entering their names followed by the `Remove` keyword. For
example, `Remove Grocery Shopping` would remove the task named "Grocery Shopping" from the list.
* Mark Task as Complete: Users can mark tasks as complete by entering their names followed by the `Complete`
keyword. For example, `MarkTask Grocery Shopping Complete` would mark the task named "Grocery Shopping" as
complete in the list.
* Display Task List: The application displays the list of tasks when the user runs it. The list is displayed in a
simple format, such as "Task 1: Grocery Shopping", "Task 2: Laundry", etc.

Requirements
------------

* Create a new C# console project in Visual Studio.
* Use the `System.Console` class to display output to the console.
* Use a dictionary or list to store the tasks and their status (complete/incomplete).
* Write functions for adding, removing, marking as complete, and displaying the task list.
* Test the application by adding, removing, and marking tasks as complete using the command-line interface.

Getting Started
---------------

1. Open Visual Studio and create a new C# console project.
2. Copy the `Program.cs` file into your project and modify it to suit your needs.
3. Add the required namespaces and references in the `Using` statements at the top of the file.
4. Modify the `Main` method to include the necessary logic for adding, removing, marking as complete, and
displaying the task list.
5. Run the application by clicking the "Run" button or pressing F5.
6. Test the application by adding, removing, and marking tasks as complete using the command-line interface.

Troubleshooting
---------------

If you encounter any issues while running the application, please refer to the following troubleshooting tips:

* Make sure you have correctly added the namespaces and references in the `Using` statements at the top of the
file.
* Check that you have written the `AddTask`, `Remove`, and `MarkComplete` methods correctly.
* Verify that you have tested the application thoroughly before running it.

Acknowledgments
---------------

This project is a personal project and does not have any external dependencies or licensing issues.

License
-------

This project is released under the MIT License. See `LICENSE` file for details.
