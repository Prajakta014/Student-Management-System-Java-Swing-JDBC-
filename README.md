# 🎓 Student Management System (Java Swing + JDBC)

A simple and efficient **Student Management System** built using **Java Swing** for GUI and **MySQL** for database management.  
This project allows admin users to manage student records easily through a desktop application.

---

## 📌 Features

- 🔐 Admin Login System
- ➕ Add New Student
- 🔍 Search Student by Roll Number
- ✏ Update Student Details
- ❌ Delete Student Record
- 📋 View All Students in JTable
- 🗄 MySQL Database Connectivity using JDBC
- ⚠ Proper Validation & Error Handling

---

## 🛠 Technologies Used

- **Java (Core + Swing)**
- **JDBC**
- **MySQL**
- **NetBeans IDE**
- **Apache Maven** (if used)

---

## 🧩 Modules

- Admin Login
- Student Registration
- Search Student
- Update Student
- Delete Student
- Database Connectivity

---

## 🗃 Database Structure

**Database Name:** `collage2`

**Table Name:** `collage`

```sql
CREATE TABLE collage (
    RollNumber INT PRIMARY KEY,
    Name VARCHAR(100),
    StudentClass VARCHAR(50)
);
