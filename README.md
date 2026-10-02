# Student-Management-System
Student Management REST API — A beginner-friendly Spring Boot project demonstrating REST API development and CRUD operations using an in-memory List as a fake database. Covers HTTP methods, request/response handling, path variables, JSON, service-controller architecture, and HTTP status codes.
# 🎓 Student Management System

A simple and efficient **Student Management System** designed to manage and organize student records digitally.

The system provides basic operations such as adding new students, viewing student details, updating existing records, searching for students, and deleting records.

---

## 📌 Features

- ➕ Add new student records
- 👀 View all student records
- 🔍 Search students
- ✏️ Update student information
- 🗑️ Delete student records
- 📋 View detailed student information
- 💾 Store student data in a database
- 🖥️ Simple and user-friendly interface
- 🔐 Basic data management and validation

---

## 🎯 Objective

The main objective of this project is to develop a system that makes student record management easier, faster, and more organized.

Instead of maintaining student information manually, the system provides a centralized digital platform where records can be managed efficiently.

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Java / Spring Boot
- **Database:** MySQL
- **IDE:** VS Code
- **Build Tool:** Maven
- **Version Control:** Git & GitHub

> Modify the technologies above according to the actual technologies used in your project.

---

## 🏗️ System Modules

### 1. Student Management

This module manages basic student information.

It allows the user to:

- Add students
- View students
- Update student details
- Delete students
- Search students

### 2. Student Records

Student records may contain:

- Student ID
- Student Name
- Roll Number
- Email
- Phone Number
- Course
- Department
- Semester
- Address
- Marks/CGPA

### 3. Database Management

All student information is stored in a database.

The database helps maintain records securely and allows quick retrieval and modification of information.

---

## 🔄 CRUD Operations

The system uses CRUD operations:

| Operation | Description |
|----------|-------------|
| Create | Add a new student |
| Read | View student information |
| Update | Modify existing student information |
| Delete | Remove a student record |

---

## 📂 Project Structure

```text
Student-Management-System/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── ...
│   │   │
│   │   └── resources/
│   │       ├── static/
│   │       ├── templates/
│   │       └── application.properties
│   │
│   └── test/
│
├── pom.xml
├── README.md
└── .gitignore
