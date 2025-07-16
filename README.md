# 👤 User Management with PHP & MySQL

## 📌 Description:
This is a simple PHP project that allows users to enter their *name* and *age*, store them in a MySQL database, and view the data in a table.  
Each row includes a *"Toggle"* button to change the user's status between 0 and 1.

---

## 🧱 Files Included:

- db.php – Main webpage with the form and table display.
- list.php – Database connection file.

---

## 🛠 How to Run:

1. *Start XAMPP*
   - Make sure *Apache* and *MySQL* are running.

2. *Create the Database*
   - Go to: http://localhost/phpmyadmin
   - Create a new database named:
     
     info
     
   - Then run this SQL to create the table:

     sql
     CREATE TABLE user (
         id INT AUTO_INCREMENT PRIMARY KEY,
         name VARCHAR(100),
         age INT,
         status INT
     );
     

3. *Place the Files*
   - Put both index.php and list.php inside a folder:
     
     C:\xampp\htdocs\user\
     

4. *Open the Web App*
   - In your browser, go to:
     
     http://localhost/user/list.php
     

---

## ✅ Features:

- Add user name and age through a form.
- Display all users in a table.
- Toggle user status (from 0 to 1 or vice versa).
- Built with plain PHP and MySQL (no frameworks used).

---
## 📷 UI Overview:

- Simple input form for name and age.
- Table view with columns: ID, Name, Age, Status, and Toggle action.
