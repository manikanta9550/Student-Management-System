# 🚀 Student Management System (JDBC + MySQL)

A simple **console-based Java application** to manage students using **JDBC** and **MySQL**.

---

## 📌 Features
✅ Add Student  
✅ View All Students  
✅ Update Student Details  
✅ Delete Student  

---

## 🛠 Technologies Used
- **Java (JDBC)**
- **MySQL Database**

---

## 📂 Project Structure
📦 Student Management System 
 ┣ 📜 DatabaseConnection.java 
 ┣ 📜 StudentDAO.java 
 ┣ 📜 StudentManagementApp.java 
 ┗ 📜 README.md


---

## 📊 Database Schema
```sql
CREATE DATABASE StudentDB;
USE StudentDB;

CREATE TABLE students (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    age INT,
    email VARCHAR(100),
    department VARCHAR(50)
);
🔗 Database Connection Setup
private static final String URL = "jdbc:mysql://localhost:3306/StudentDB";
private static final String USER = "root";
private static final String PASSWORD = "yourpassword";
🚀 How to Run
javac StudentManagementApp.java
java StudentManagementApp
🖥️ Console Menu
1 → Add Student  
2 → View All Students  
3 → Update Student  
4 → Delete Student  
5 → Exit  
🔮 Future Enhancements
 🎨 Add GUI with JavaFX
 🌐 Convert to a Spring Boot Web App
 ⚡ Use Connection Pooling (HikariCP)





