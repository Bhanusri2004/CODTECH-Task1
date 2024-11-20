**Name: BHANUSRI G
Company : CODTECH IT SOLUTIONS PVT.LTD
ID : CT08DS9625
Domain : Software Development
Duration : 10 Nov 2024 - 10 Dec 2024**

**Task - 1 --- Task Management Tool**
**Introduction**
The Task Management Tool is a console-based Java application designed to help users manage their daily tasks effectively. This application allows users to add, view, and delete tasks in a simple and user-friendly interface.

**Features**
Add Task: Create a task by providing a title and description.
View All Tasks: Display all the tasks stored during the session.
Delete Task: Remove a specific task by its index.
Exit: Exit the application safely.

**Technologies Used**
Programming Language: Java
IDE: Any Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans)
Execution Environment: Console Application
Code Explanation
Main Functionalities
The program revolves around a Task class to represent individual tasks, and it uses an ArrayList to store and manage the tasks. Below is a breakdown of the features:

**Code Snippet**

System.out.println("\nTask Management Tool");
System.out.println("1. Add Task");
System.out.println("2. View All Tasks");
System.out.println("3. Delete Task");
System.out.println("4. Exit");
System.out.print("Enter your choice: ");
choice = scanner.nextInt();
This snippet shows how the main menu options are presented to the user.

**How to Run**
Clone or download the repository.
Open the code in a Java IDE (e.g., IntelliJ IDEA, Eclipse).
Compile and run the program.
Use the menu to add, view, and manage tasks.

**Sample Output**

Task Management Tool
1. Add Task
2. View All Tasks
3. Delete Task
4. Exit
Enter your choice: 1
Enter Task Title: Buy Groceries
Enter Task Description: Purchase vegetables and fruits.
Task added successfully!

Enter your choice: 2
All Tasks:
1. Title: Buy Groceries
   Description: Purchase vegetables and fruits.
Possible Enhancements
Save tasks permanently using file handling or a database.
Implement task priorities and deadlines.
Add a search or filter feature for tasks.
Build a graphical user interface (GUI) for better usability.

**Conclusion**
The Task Management Tool is a lightweight Java application demonstrating fundamental programming concepts such as object-oriented design, data storage using ArrayList, and user interaction through menus. It can be further extended into a robust task management system.

This overview can be copied into your GitHub repository's README.md file for the Task Management Tool project. Let me know if you need further assistance! 😊
