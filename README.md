# 📚 Library Management System

This is a simple console-based Library Management System written in C++. The system allows users to manage books and student records. It includes features such as adding, modifying, and deleting book and student records, issuing and depositing books, and an administrator menu for more extensive operations.

## 📁 Files

1. **main.cpp:** The main program file containing the menu and overall flow of the system.
2. **book.h:** Header file for the `book` class, which represents a book and includes methods for creating, displaying, modifying, and reporting book details.
3. **student.h:** Header file for the `student` class, which represents a student and includes methods for creating, displaying, modifying, and reporting student details.
4. **functions.h:** Header file containing various functions for file handling, displaying specific records, modifying records, and more.
5. **README.md:** This file, providing an overview of the project.

## 🧑‍💻 Classes

1. **book class:** Represents a book with attributes like book number, name, and author. Includes methods for creating, displaying, modifying, and reporting book details.

2. **student class:** Represents a student with attributes like admission number, name, and token count. Includes methods for creating, displaying, modifying, and reporting student details.

## 🔧 Functions

1. **write_book():** Function to write book records to the file.
2. **write_student():** Function to write student records to the file.
3. **display_spb(char n[]):** Function to display specific book details.
4. **display_sps(char n[]):** Function to display specific student details.
5. **modify_book():** Function to modify book records.
6. **modify_student():** Function to modify student records.
7. **delete_student():** Function to delete a student record.
8. **delete_book():** Function to delete a book record.
9. **display_alls():** Function to display all student records.
10. **display_allb():** Function to display all book records.
11. **book_issue():** Function to issue a book to a student.
12. **book_deposit():** Function to deposit a book from a student.

## 🚀 Usage

1. Run the program.
2. Choose options from the main menu to perform different operations.

Feel free to explore and enhance the system as needed!
