📝 React To-Do List Project
This is a To-Do List web application built using React JS. It helps users manage their daily tasks by allowing them to add, delete, and reorder tasks.

✅ Project Objective
The purpose of this project is to demonstrate how to:

Use React hooks (useState) for state management.

Handle user input in forms.

Dynamically display a list of items.

Update and manipulate arrays (add, delete, move items).

📚 Explanation of the Code
useState Hooks
The project uses two main pieces of state:

tasks: This holds the current list of tasks.

newTask: This stores the text typed by the user in the input field, representing a new task to add.

Functions in This Project
handleInputChange: Updates the state of newTask every time the user types in the input field. This allows for a controlled component where the input field's value is directly tied to the state.

addTask: Adds the task entered by the user to the list, ensuring that empty tasks are not added by checking the input before updating the list.

deleteTask: Allows users to delete a task from the list. The function filters out the task based on its index, creating a new array without that task and updating the state.

moveTaskUp: Enables users to move a task upwards in the list. This function swaps the position of the task with the one above it, modifying the order of the array.

moveTaskDown: Similar to moving tasks up, this function allows the user to move a task down in the list by swapping it with the one below it.

🎨 User Interface (UI)
The user interface includes:

An input field where users type a new task.

An "Add" button that adds the task to the list.

Each task in the list has:

A Delete button to remove the task.

A Move Up button to shift the task upwards.

A Move Down button to shift the task downwards.

The list updates dynamically as the state changes, offering an interactive and responsive experience.

🚀 Features Implemented
Users can add new tasks.

Users can delete tasks.

Users can move tasks up and down to reorder the list.

Prevents empty task submission by checking the input before adding.

The task list is rendered dynamically using React's state management and hooks.

🙋‍♂️ About the Author
This project was built by Madhan as part of learning React fundamentals, focusing on state management and dynamic list operations.
