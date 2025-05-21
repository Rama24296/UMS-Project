## UNIVERSITY SYSTEM MANAGEMENT-CONSOLE-BASED

A simple, menu-driven University College Management System built using Python's object-oriented programming concepts. This program allows you to manage colleges, students, and teachers via a command-line interface.

---

## 📌 Features

- ✅ Create new colleges
- 👨‍🎓 Add students with roll number, name, branch, and job update
- 👩‍🏫 Add teachers with roll number, name, and subject
- 📋 Display all students or teachers in a college
- 🔍 Search for:
  - A teacher by name to get their subject
  - A student by name to check if they exist
- ❌ Exit the system anytime

---

## 🧱 Class Structure

### `person`
Base class for common attributes.

- `rollno`: Unique identifier
- `name`: Person's name

### `student(person)`
Inherits from `person`.

- `branch`: Student's department
- `jobupdate`: Job placement/status

### `teacher(person)`
Inherits from `person`.

- `subject`: Subject taught by the teacher

### `college`
Manages collections of students and teachers.

- `cname`: College name
- `students`: List of `student` objects
- `teachers`: List of `teacher` objects
- Methods:
  - `add_student()`
  - `add_teacher()`

---

## 🚀 How to Run

1. Make sure Python 3 is installed.
2. Save the code in a file, e.g., `UMS.py`.
3. Run the file using the terminal:

```bash
python UMS.py

## Use the interactive menu to perform actions.

1. Create College
2. Add Student
3. Add Teacher
4. Display Students
5. Display Teachers
6. Get Teacher's Subject by Name
7. Check if Student Exists
8. Exit
