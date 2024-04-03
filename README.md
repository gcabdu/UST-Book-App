# UST-Book-App

Hey there! Welcome to UST Books. This is like the Swiss Army knife for managing books at our uni. Whether you're a student who needs to get books or an employee handling the book chaos, we got you covered.

## Features

- **User Authentication**: Separate login portals for students (StudentLogin) and employees (EmployeeLogin).
- **Student Services**: Any student can access their accounts through `Student` instances to interact with book orders and related services.
- **Employee Services**: Employees have the ability to handle ongoing orders and create support tickets through the `Employee` class.
- **Administrative Functions**: Administrators (Admin) can add new books, universities, departments, and courses to the system.
- **Super Administrator Capabilities**: Super Administrators (`SuperAdmin`) has the ability to manage employee records and create new employees if need be.
- **Database Integration**: Uses SQLite (`ustbooks.db`) for data persistence, managing user details, and book orders.
- **GUI**: A graphical user interface implemented with Tkinter for easy navigation and interaction with the system.

## Requirements

- Python 3.x
- SQLite3
- Tkinter
- PIL (Python Imaging Library)

## Setup

1. Make sure Python 3.x and PIL are installed on your system.
2. Clone the repository to your local machine.
3. Navigate to the directory containing `main.py`.
4. Run `main.py` using Python to start the application.
