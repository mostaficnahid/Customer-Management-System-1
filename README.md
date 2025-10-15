Customer Management System in C
A simple, console-based application for managing customer data, built entirely in the C programming language. This project serves as a capstone demonstration of core programming concepts, including file handling, data structures, and user input management.

Table of Contents
Project Overview

Key Features

Technologies Used

Prerequisites

How to Compile and Run

How to Use the System

File Structure

Future Improvements

Author

Project Overview
This Customer Management System is a command-line application designed to handle essential customer records. It provides a straightforward, menu-driven interface that allows users to perform standard CRUD (Create, Read, Update, Delete) operations. All customer data is persistently stored in a local file (customers.dat), ensuring that information is saved between sessions. This project showcases the practical application of C for building functional, data-oriented programs without relying on external databases or complex frameworks.

Key Features
Add New Customer: Create a new record by entering customer details like name, contact number, and email address.

View All Customers: Display a formatted list of all existing customer records stored in the system.

Search for a Customer: Find a specific customer by searching for their name or contact number.

Update Customer Information: Modify the details of an existing customer record.

Delete a Customer: Remove a customer record permanently from the system.

Persistent Data Storage: All records are saved to a file, so data is not lost when the program closes.

Technologies Used
Programming Language: C (Standard C99)

Compiler: GCC (GNU Compiler Collection) or any standard C compiler.

Core Concepts:

File I/O (fopen, fwrite, fread, fclose)

Structs for data modeling

Pointers and memory management

Standard I/O Library (stdio.h)

String Manipulation (string.h)

Prerequisites
To compile and run this project, you will need a C compiler installed on your system. The most common one is GCC.

For Windows: You can install MinGW (Minimalist GNU for Windows) or use WSL (Windows Subsystem for Linux).

For macOS: Xcode Command Line Tools include the Clang compiler, which is compatible.

For Linux: GCC is typically pre-installed. If not, you can install it using your distribution's package manager (e.g., sudo apt-get install gcc on Debian/Ubuntu).

How to Compile and Run
Clone or Download the Repository:
Get a local copy of the project files.

Navigate to the Project Directory:
Open your terminal or command prompt and change to the directory where the source code is located.

cd path/to/your/project

Compile the Source Code:
Use the gcc command to compile the .c file into an executable.

gcc main.c -o customer_management

(Replace main.c if your main source file has a different name.)

Run the Executable:
Execute the compiled program from the terminal.

On Linux/macOS:

./customer_management

On Windows:

customer_management.exe

This will start the application and display the main menu.

How to Use the System
Once the application is running, you will be presented with a main menu of options:

=====================================
    CUSTOMER MANAGEMENT SYSTEM
=====================================
[1] Add a New Customer
[2] List All Customers
[3] Search for a Customer
[4] Update a Customer's Record
[5] Delete a Customer
[0] Exit
=====================================
Enter your choice:

Simply type the number corresponding to the action you want to perform and press Enter.

Follow the on-screen prompts to enter customer data or search queries.

The system will provide feedback on whether your operations were successful.

File Structure
.
├── main.c              // Main C source code file containing all logic
├── customers.dat       // Data file where customer records are stored (created on first run)
└── README.md           // This file

Future Improvements
This is a foundational project with many opportunities for expansion. Potential future enhancements include:

Error Handling: Implement more robust input validation and error checking.

Sorting: Add functionality to sort the customer list by name or ID.

User Interface: Port the application to a simple GUI library like GTK or Dear ImGui for a more user-friendly experience.

Data Encryption: Encrypt the customers.dat file to protect sensitive customer information.

Modular Code: Refactor the code into separate .h and .c files for better organization and maintainability.

Author
Your Name: Mostafic Yellahy Nahid

GitHub: [mostaficnahid](https://github.com/mostaficnahid)

LinkedIn: https://www.linkedin.com/in/mostafic-yellahy-nahid-46a0202b5/
