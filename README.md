# University-Course-Management-System
comprehensive course management system that demonstrates database fundamentals,  security best practices, and transaction management.
This is a simple, web-based system for managing student data, course enrollment, and grades, built using PHP and MySQL. It demonstrates using layered architecture (DAO and Service) and secure ACID transactions for critical processes.

##Key Features:
* Student Dashboard: View student details and current enrollments using a Student ID.
* Secure Enrollment: Enroll students into courses while automatically checking capacity and student status. 
* Enrollment is handled as a secure transaction (ACID).
* Modular Design: Separates the database work ($\text{DAO}$) from the business rules ($\text{Service}$) for clean code.
