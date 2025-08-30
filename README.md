 Student Registration System
Name: Bassey Sampson Felix  
Matric Number: 23/CSC/053  
Course Code: CSC 282  
Assignment Title: Student Registration Web Application  

Project Description
This is a simple PHP web application for registering students into a MySQL database.  
It includes:
- A form to register students.
- Validation for required fields and valid email.
- A page to view all registered students.
- Ability to delete student records (extra credit).

 Setup Instructions
 1. Requirements
- PHP (7.x or later)
- MySQL
- Web server (XAMPP/WAMP/LAMP or MAMP recommended)
- Git (optional, for cloning)

 2. Database Setup
1. Open phpMyAdmin ([http://localhost/phpmyadmin](http://localhost/phpmyadmin))  
2. Create a database called `student_db_sammy` (or any name you choose).  
3. Import the file `student_db.sql` located in the project folder.  
   - This will create the `student_records` table automatically.  

 3. Running the Application
1. Place the project folder inside your server’s `htdocs` (for XAMPP) or `www` (for WAMP/MAMP).  
2. Start Apache and MySQL in XAMPP Control Panel.  
3. Open your browser and go to:  http://localhost/student_app_friend/index.php
4. . Register a student using the form.  
5. Click View Registered Students to see all records.  

 4. Features
- ✅ Student registration form  
- ✅ Validation (all fields required, email format check)  
- ✅ Display registered students  
- ✅ Delete option beside each record  

Project Structure
student_app_friend/
│── index.php  Student registration form
│── process.php  Handles form submission & inserts into DB
│── view.php  Displays registered students & delete option
│── style.css Stylesheet for UI
│── student_db.sql # Database script
│── README.md  Project documentation


Author
Bassey Sampson Felix  
Matric No: 23/CSC/053  

