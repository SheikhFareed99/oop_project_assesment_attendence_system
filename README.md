Student Management System (C++ OOP Project)
Overview

This project is a Student Management System built using C++ with Object-Oriented Programming principles.
It allows management of students, teachers, attendance, quizzes, assignments, grades, mid-term and final exams, and also provides role-based access for admins, teachers, and students.

Features
1. Admin Features

Login using credentials:

Username: admin

Password: admin

Manage students:

Add, remove, update student information

View all student data

Track students who have left or been expelled

Manage teachers:

Add, remove, update teacher information

View teacher list

Notes system:

Send notes to teachers or students

Get notes received

Password management:

Update passwords for faculty or students

Admin profile:

Update and print admin profile

2. Teacher (Faculty) Features

Login using personal credentials

Manage student academic data:

Add attendance

Add grades for quizzes, assignments, midterms, and finals

Search for student information by ID

Handle students in their assigned sections

3. Student Features

Login using personal credentials

View profile

View grades, attendance, and notes

Track performance in quizzes, assignments, midterms, and finals

Technical Details

Language: C++

Programming Paradigm: Object-Oriented Programming (OOP)

File Handling: Stores credentials, student, and teacher data in text files

UI: Console-based with color highlights (Windows)

Error Handling: Basic exception handling for invalid input

Classes and Structure

admin → Handles admin operations and profile management

faculty → Handles teacher operations and section data

passwordManager → Template class for login and password management

student → Stores and manages student data including attendance, grades, and exam scores

Utility functions:

add_students(), remove_student(), update_student(), see_data()

send_notes(), get_notes()

faculty_duty() → Handles teacher-specific tasks

student_profile() → Handles student-specific tasks

Installation and Running

Clone or download the repository

Open in any C++ IDE (e.g., Code::Blocks, Visual Studio, or VS Code with C++ extension)

Ensure all .cpp and .h files (including project.h) are in the same directory

Compile and run main.cpp

Follow the console menu:

Enter 1 for Admin

Enter 2 for Faculty

Enter 3 for Student

Enter 4 to exit

Note:

Admin login: admin/admin

Teacher and student login credentials are stored in credentials.txt

Usage

Admin can fully manage the system and view all records.

Teachers can manage only their assigned students and sections.

Students can view their own records, grades, and attendance.

Passwords and notes system provide secure communication and management.

Future Improvements

Add a GUI interface for easier usability

Use databases (MySQL/SQLite) instead of text files for better scalability

Add report generation for student grades and attendance

Implement role-based access control with encryption for credentials
