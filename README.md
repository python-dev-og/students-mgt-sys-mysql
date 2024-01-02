[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/release/python-3110/)
[![PyQt6](https://img.shields.io/badge/PyQt6-41CD52.svg?&logo=qt&logoColor=white)](https://riverbankcomputing.com/software/pyqt/intro)
[![SQLite](https://img.shields.io/badge/SQLite-07405E.svg?&logo=sqlite&logoColor=white)](https://www.sqlite.org/index.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Student Management System App

## Overview
This Python application is a Student Management System built using PyQt6. It offers functionalities such as adding, searching, editing, and deleting student records in a MySQL database. The GUI is designed to be user-friendly and efficient for managing student data.

## Features
- **Add Student**: Register new student records.
- **Search Student**: Search for students by name.
- **Edit Student Data**: Update existing student records.
- **Delete Student Data**: Remove student records from the database.
- **Dynamic Data Loading**: Automatically loads and refreshes data from the SQLite database.
- **User-Friendly Interface**: Offers a clean and intuitive graphical user interface.

## Requirements
- Python 3.x
- PyQt6
- MySQL

## Installation
1. Clone or download the repository.
2. Install required dependencies:
   ```bash
   pip install PyQt6
   ```
   ```bash
   pip install mysql-connector-python
   ```

3. Run the application:
   ```bash
   python main.py
   ```

## Usage
Upon launching the application, the main window will display a table of student records. From the toolbar or menu, you can add, search, edit, or delete students. Selecting a student record from the table will enable edit and delete options.

### Adding a Student
Click on 'Add Student' and fill in the details in the dialog box that appears. Press 'Register' to add the student to the database.

### Searching for a Student
Use the 'Search' option to find students by name. The results will be highlighted in the main table.

### Editing a Student
Select a student from the table and click 'Edit Record'. Modify the details in the dialog box and click 'Update' to save changes.

### Deleting a Student
Select a student and click 'Delete Record'. Confirm the deletion in the dialog box.

## Database Schema
The application uses a SQLite database with a single table `students`:
- `id`: Integer, Primary Key
- `name`: Text
- `course`: Text
- `mobile`: Text

## Customization
The code is structured for easy customization. You can modify the UI elements, database schema, or add new features as per your requirements.

## Contribution
Contributions to enhance the application or fix bugs are welcome. Please follow standard coding practices and submit pull requests for review.

## License
This project is open-sourced under the MIT License. Feel free to use, modify, and distribute the code.

---

For detailed documentation on PyQt6 and SQLite3, please refer to their official documentation.

## Final look

![Screenshot 2024-01-01 at 10.34.28 PM.png](images%2FScreenshot%202024-01-01%20at%2010.34.28%E2%80%AFPM.png)

![Screenshot 2024-01-01 at 10.35.45 PM.png](images%2FScreenshot%202024-01-01%20at%2010.35.45%E2%80%AFPM.png)

![Screenshot 2024-01-01 at 10.36.06 PM.png](images%2FScreenshot%202024-01-01%20at%2010.36.06%E2%80%AFPM.png)