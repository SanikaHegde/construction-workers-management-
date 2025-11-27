
# 🏗️ Construction Workers Management System (PHP/MySQL) 

The **Construction Workers Management System** is a simple web-based application built using **PHP & MySQL**.  
It helps construction businesses manage their projects, employees, and work divisions efficiently.  

This system allows monitoring of project progress, deadlines, team assignments, and employee details, making it easier for companies to stay organized.  

---     
 
📌 Features 
---

- **Login Page** – Secure authentication for system users.  
- **Home Page** – Displays system dashboard, reminders, and deadline notifications.  
- **Employee List Page** – Manage and view all company employees.  
- **Position Page** – Add and update employee positions.  
- **Project Division Page** – Manage different project divisions (layout, landscape, etc.).  
- **Project Team Page** – Organize project teams and assign members.  
- **Project List Page** – View and manage all projects with status and details.  
- **Users Page** – Admin panel to manage system users.  
- **Reminders & Notifications** – Alerts for upcoming deadlines (15 days before) and overdue projects.  

---
 🛠️ Tech Stack
---
* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL
* **Server:** Apache (XAMPP/WAMP)

---
⚙️ Installation Guide 
---
  
1. **Download or Clone Repository**
   bash
   git clone https://github.com/SanikaHegde/construction-workers-management.git
2. **Move Project to Server Directory**
   * For **XAMPP**: move the project folder to
     C:\xampp\htdocs\
   * For **WAMP**: move the folder to
     C:\wamp\www\
3. **Create Database**
   * Open **phpMyAdmin**
   * Create a new database, for example:
     construction_db
4. **Import SQL File**
   * Inside the project folder, find the SQL file (e.g., `database.sql`).
   * Import it into your newly created database.
5. **Configure Database Connection**
   * Open `config.php` (or database connection file in project).
   * Update with your database credentials:
     php
     $servername = "localhost";
     $username   = "root";
     $password   = "";
     $dbname     = "construction_db";
6. **Run the Project**
   * Start **Apache** & **MySQL** in XAMPP/WAMP.
   * Visit in browser:
     http://localhost/construction-workers-management/

---

