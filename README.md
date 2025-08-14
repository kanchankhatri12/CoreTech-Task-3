# CoreTech-Task-3
This project is a simple full-stack web application for registering students and viewing the registered list. It uses HTML, CSS, PHP, and MySQL with a black &amp; gold luxury theme for a premium look.
Features
Student Registration Form with fields:

Name

Email

Roll Number

Department (dropdown)

Form Validation (empty field checks, valid email format)

Stores data in MySQL database (students table)

View Registered Students in a table format

Delete Function to remove student entries

Stylish VVIP black & gold UI

🛠️ Technologies Used

Frontend: HTML, CSS

Backend: PHP

Database: MySQL

📂 Steps to Set Up the Project
1. Database Setup

Create a database:

CREATE DATABASE internship_db;


Create the students table:

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL,
    roll_number VARCHAR(50) NOT NULL,
    department VARCHAR(100) NOT NULL
);

2. File Structure
student_app/
│── db_connect.php       # Database connection file
│── index.php            # Student registration form
│── view_students.php    # View & delete registered students
│── style.css            # Black & gold theme styling

3. Running the Project

Place the project folder in your XAMPP or WAMP htdocs directory.

Start Apache & MySQL from the control panel.

Import the database into phpMyAdmin.

Open the project in your browser:

http://localhost/student_app/index.php


Gold-glow hover effects and premium UI
