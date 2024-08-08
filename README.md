**Name|** SAMANJOY DAS
**Company|** CODTECH IT SOLUTIONS
**ID|** CTO8PP919
**Domain|** Python Programming
**Duration|** June to August 2024
**Mentor|** SRAVANI GOUNI


## Overview of the Project

### Project: Student Grade Tracker

### Objective
The Student Grade Tracker is a Python-based desktop application designed to help students or educators track and manage grades for various subjects. The application allows users to input subjects and corresponding marks, and then calculates the overall average, assigns a letter grade, and determines the GPA on a 4.0 scale.

### Key Activities

**Input Student Name:** The application begins by prompting the user to enter the student's name.
**Add Subjects and Marks:** Users can add multiple subjects along with their corresponding marks.
**Calculate Grades:** After entering the subjects and marks, the application calculates the average marks, assigns a letter grade, and computes the GPA.
**Display Results:** The application displays the calculated average marks, letter grade, and GPA for the student.
**Restart Functionality:** Users can restart the application to track another student's grades.

### Technologies Used

**Python:** The core programming language used to build the application.
**Tkinter:** A standard GUI library in Python, used for creating the application's graphical user interface.
**ttk (Themed Tkinter Widgets):** Provides enhanced styling options for the Tkinter widgets used in the application.
### Working of the Code
**Initialization:** The GradeTracker class is initialized with a Tkinter root window, setting up the application's title and preparing for UI elements.

### User Interface Setup:

**Initial UI:** The user is prompted to enter the student's name. Upon entering and confirming, the UI transitions to the subject and marks input interface.
**Subject and Marks Entry:** The user can input the subject name and corresponding marks. The data is stored and displayed in a Treeview widget.

### Grade Calculation:

Once all subjects and marks are entered, the user can calculate the grades.
The program calculates the total and average marks, determines the letter grade based on the average, and calculates the GPA using a 4.0 scale.
**Displaying Results:** The results, including average marks, letter grade, and GPA, are displayed in a final summary screen.

**Restart Option:** The user has the option to restart the process for a new student by clicking the "Restart" button.
