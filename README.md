# 📚 Library Management System

A simple web-based Library Management System built using HTML, CSS, PHP, and MySQL. This project allows library administrators to manage book inventory, issue and return books, and maintain member records.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3
- **Backend**: PHP 7+, JavaScript
- **Database**: MySQL
- **Tools**: XAMPP / WAMP / LAMP for local development

---

## 📌 Features

- 📖 Add, Edit, Delete books
- 👤 Member registration and management
- 🔄 Issue and return books with due date tracking
- 📊 View all transactions and book history
- 🗂️ Search functionality for books and members
- 🛡️ Basic login system for admin

---

## 🏁 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sWAGish/Library-Management-System.git


2. Import the Database
Open phpMyAdmin

Create a new database (e.g., library_db)

Import the project.sql file located in the root folder

3. Run Locally
Place the project folder in htdocs (XAMPP) or www (WAMP)

Start Apache and MySQL from the control panel

Visit: http://localhost/Library-Management-System

🔐 Admin Login
Username: admin

Password: admin123

(Update from the database manually or build a secure login module for production use.)

📁 Folder Structure
Library-Management-System/
├── Source/               # Core PHP and HTML files
├── project.sql           # MySQL database dump
├── README.md             # Project documentation
├── .htaccess             # (optional) URL rewriting
