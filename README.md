# University-Course-Management-System
This is a simple, web-based system for managing student data, course enrollment, and grades, built using PHP and MySQL. It demonstrates using layered architecture (DAO and Service) and secure ACID transactions for critical processes.

## Key Features:
* Student Dashboard: View student details and current enrollments using a Student ID.
* Secure Enrollment: Enroll students into courses while automatically checking capacity and student status. 
* Enrollment is handled as a secure transaction (ACID).
* Modular Design: Separates the database work DAO from the business rules Service for clean code.

## Setup Guide 
you will need to download XAMPP/WAMP (or similar) with PHP and MySQL running locally.
### Step 1: Download files
* Place the entire folder into your web server's root directory (e.g., C:\xampp\htdocs\university-course-management-system).
### Step2: Database Setup
* Open phpMyAdmin and create a new database named university_db
* Run SQL code within the file called university_schema.sql
* Configure connection
  ** Open the config/database.php file.
  ** Update the DB_USER and DB_PASS with your local MySQL credentials.
### Step 3: Run the Application
* Open your browser and navigate to the student dashboard:http://localhost/university-course-management-system/student_dashboard.php

## Enhanced Entitiy Relationship Diagram 
<img width="2360" height="1068" alt="Untitled Diagram" src="https://github.com/user-attachments/assets/9fa84ffb-0dbb-4eed-ae42-7d7a9b5cc1fd" />

