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

## Interfaces
### Home page
* <img width="1773" height="524" alt="image" src="https://github.com/user-attachments/assets/a4a11de8-e66b-41f0-82df-1a3d3ee3d855" />
### Student interface
* <img width="1864" height="555" alt="image" src="https://github.com/user-attachments/assets/3a05a708-65f7-45a2-92af-d2b16ed649bf" />
* <img width="614" height="640" alt="image" src="https://github.com/user-attachments/assets/6c51d7b5-185b-4eb1-883f-fa5f16ece9cf" />
* <img width="901" height="324" alt="image" src="https://github.com/user-attachments/assets/36ef7673-19ac-46ad-830c-aa62ac66c35a" />
* <img width="873" height="854" alt="image" src="https://github.com/user-attachments/assets/48b61fe7-88fb-414c-ba63-24a744f17ed9" />
* <img width="614" height="482" alt="image" src="https://github.com/user-attachments/assets/e0ebb358-5759-4de7-ae3c-e5751627c3d5" />
### Admin interface
* <img width="1711" height="512" alt="image" src="https://github.com/user-attachments/assets/781efe7e-92d2-43b7-9039-fb95184bbb4d" />
* <img width="1009" height="600" alt="image" src="https://github.com/user-attachments/assets/c456b558-ff36-4057-bc3a-15b51483b37e" />
* <img width="751" height="881" alt="image" src="https://github.com/user-attachments/assets/705ff4e5-22fc-4ca0-95f9-1f272910c127" />
* <img width="330" height="335" alt="image" src="https://github.com/user-attachments/assets/0557aec1-dd6e-45a5-91fe-f73a6925817d" />




