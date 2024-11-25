# Employee Management System

## Overview

This Employee Management System is a simple C++ console application designed to manage employee records. It provides functionalities such as adding, modifying, deleting, and displaying employee data. The system also includes a secure login and registration mechanism for authorized access.

---

## Features

- **Login and Registration**:

  - Secure login using a username and password.
  - New users can register by entering their name and password.

- **Employee Management**:

  - **Add Employee**: Add a new employee record to the system.
  - **View Employee**: Display all employee records.
  - **Modify Employee**: Edit the details of an existing employee.
  - **Search Employee**: Search for a specific employee by their ID.
  - **Delete Employee**: Remove an employee record from the system.

- **File-Based Storage**:
  - Employee records are saved in a text file (`Employee_Record.txt`).
  - Login credentials are saved in a file (`Ep_data.txt`).

---

## Requirements

- Compiler: Any C++ compiler (e.g., GCC, Visual Studio, MinGW).
- Libraries:
  - Standard C++ libraries.
  - Windows-specific headers (`windows.h`).

---

## How to Run

1. **Compile the Code**:
   Compile the C++ source code using your preferred compiler.

   Example:

   ```bash
   g++ employee_management.cpp -o employee_management
   ```
