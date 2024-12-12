Company: CODETECH IT SOLUTIONS 
ID: CT6WDS2401 
Domain: Python Programming 
Duration: November 20th,2024 to January 5th,2025
Mentor:

Overview of the Project
Project:STUDENT GRADE TRACKER

Objective:-
The goal of this program is to help users manage student grades efficiently. 
It allows users to:
Add or edit grades for various subjects.
View grades by subject.
Generate a detailed performance report.
Save data persistently to ensure grades are not lost when the program is closed.

Key Features:-
1) Add/Edit Grades: Users can input grades for subjects or update existing ones.
2) Display All Grades: Shows all recorded grades organized by subject.
3) Generate Reports:
Highlights the highest and lowest grades.
Calculates the average grade.
Provides a letter grade and GPA based on the average.
4) Persistent Data Storage:
Grades are saved to a file (grades.json) so they are not lost when the program exits.
Data is automatically loaded when the program starts.
5) Error Handling:
Ensures grades entered are valid numbers between 0 and 100.
Handles file-related errors (e.g., missing file for loading grades).
6) User-Friendly Menu: A simple menu allows users to navigate and perform actions easily

Technologies Used:-
1)Python Standard Library:
->json for persistent data storage.
->input() for user interaction.
->Built-in functions like max() and min() for data analysis.

2)Programming Concepts:
->File handling for saving and loading data.
->Dictionaries for efficient storage and lookup of grades.
->Control structures (loops and conditionals) for menu-based navigation.
->Modular functions for code organization.

Advantages:-
1)Ease of Use: A simple menu makes the program user-friendly.
2)Data Persistence: Grades are saved automatically, so they are not lost after exiting.
3)Scalability: Can be extended with advanced features like weighted GPA or multi-user support.
4)Modularity: Functions are modular, making the program easy to maintain and extend.

Key Variables:-
Here are the key variables in the **Student Grade Manager** program and their purposes:

1)FILENAME
Purpose: Stores the name of the file (grades.json) where the grades are saved for persistence.
2)grades
Purpose: A dictionary that holds the subject names as keys and their respective grades as values.
3)subject
Purpose: Temporarily holds the name of a subject when adding or editing grades.
4)grade
Purpose: Temporarily holds the numeric grade for a specific subject (value between 0 and 100).
5)choice
Purpose: Stores the user's menu option input to determine which action to perform (e.g., add grade, view grades, etc.).
6)average
Purpose: Holds the calculated average of all grades for generating performance reports.
7)highest
Purpose: Stores the subject and grade with the highest score for the performance report.Example: ("Math", 95)
8)lowest
Purpose: Stores the subject and grade with the lowest score for the performance report.
9)letter
Purpose: Stores the calculated letter grade (e.g., A, B, C) based on the average grade.
10)gpa
Purpose: Stores the GPA equivalent of the average grade.


