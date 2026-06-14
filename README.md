Student Manager with JSON Storage

A beginner-friendly Python project that demonstrates how to build a Student Management System with permanent data storage using JSON files.

📌 Description

This program allows users to:

Add students
Search students
View all students
Delete students
Save student records permanently
Load student records automatically on startup
Exit the application safely

Student data is stored in a file named students.json, ensuring records remain available even after the program is closed.

🧠 Concepts Used

Dictionaries
Nested Dictionaries
JSON Files
json.load()
json.dump()
File Handling
Exception Handling
try-except
FileNotFoundError
CRUD Operations
Menu-Driven Programming
User Input Validation

💻 Features

✅ Add Student Records

✅ Search Students

✅ View All Students

✅ Delete Students

✅ Automatic Data Loading

✅ Permanent Data Storage

✅ Total Student Counter

✅ Error Handling

✅ Menu System

📂 Files Used

student_manager.py
students.json

▶️ Example Output

===== STUDENT MANAGER =====

1. Add Student
2. Search Student
3. View All Students
4. Show All Students
5. Delete Student
6. Exit

Total students: 0
Enter choice: 1

Enter name: Rahul
Enter age: 16
Enter city: Kolkata
Enter class: 9

Student Added!
Enter choice: 2

Search student: Rahul

{'age': '16', 'city': 'Kolkata', 'class': 9}
Enter choice: 6

Data saved successfully!
Exiting...

🎯 Learning Outcome

By building this project, you will learn:

How to work with JSON files
How to save and load data permanently
How CRUD applications work
How to use nested dictionaries
How to handle file errors
How to build real-world management systems
