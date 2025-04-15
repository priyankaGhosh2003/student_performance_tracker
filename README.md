# 🎓 Student Academic Performance Management System (CLI-Based)

This is a **Command-Line Based Student Academic Performance Management System** built using **Python**, **SQLite**, and **Matplotlib**. It helps manage academic records of students, allowing different access levels for **admins**, **teachers**, and **students**.

---

## 📌 Features

### 🛠 Admin Portal
- Add/View/Manage:
  - Students
  - Teachers
  - Subjects
  - Classes
- View records from all tables

### 👨‍🏫 Teacher Portal
- Login with teacher ID
- View subjects assigned
- Upload marks for students (subject-wise)
- View ranked list of students by average percentage
- Visualize student performance distribution (Matplotlib bar chart)
- Export student performance reports as PDF

### 🧑‍🎓 Student Portal
- View subject-wise marks by entering student ID

---

## 🧰 Technologies Used
- **Python 3.x**
- **SQLite3** (as a lightweight relational database)
- **Matplotlib** (for data visualization)
- **Tkinter** (optional file dialog usage)
- **FPDF** (for generating PDF reports)

---

## 🗃 Database Schema Overview

- `students(student_id, student_name, class_name)`
- `teachers(teacher_id, teacher_name)`
- `subjects(subject_id, subject_name, class_name, teacher_id)`
- `marks(student_id, subject_id, marks)`

All foreign key relationships are enforced to ensure data consistency.

---

## 🏁 How to Run the Project

1. Clone the repo or download the code.
2. Ensure you have Python 3 installed.
