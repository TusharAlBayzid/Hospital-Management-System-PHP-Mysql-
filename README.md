# Hospital-Management-System-PHP-Mysql-
A professional Hospital Management System built with PHP, MySQL, and Bootstrap 5. Features separate dashboards for Admin, Doctor, and Patient with secure database management.

Project Overview
This Hospital Management System (HMS) is a comprehensive web-based application designed to digitalize and streamline daily hospital operations. It provides a structured platform to manage patient registrations, doctor appointments, and administrative records through a secure database.

Contributors
Bayzid

Amith

Key Modules & Features
Admin Dashboard:

Manage doctor profiles and review job applications.

Monitor hospital finances and track total income.

Doctor Panel:

View and manage patient appointment schedules.

Accept or reject appointment requests from patients.

Patient Portal:

Online account registration and secure login.

Book appointments with specialized doctors and view personal health records.

Modern UI/UX:

Features a responsive design built with Bootstrap 5.3 for compatibility across all devices.

Professional homepage with a smooth cross-fade image slider.

Technology Stack
Frontend: HTML5, CSS3, JavaScript, Bootstrap 5.3.

Backend: PHP.

Database: MySQL.

Icons: Font-Awesome 6.6.0.

Database Schema
The system uses a relational database architecture with the following core tables:

admin: Stores administrative login credentials and profiles.

doctors: Contains specialist information, salary details, and account status.

patient: Manages personal details and credentials of registered patients.

appointment: Records appointment dates, symptoms, and current status.

income: Tracks payments, discharge dates, and descriptions.

Installation & Setup
To run this project locally, follow these steps:

Clone the Repository:

Bash

git clone https://github.com/your-username/hms-project.git
Move to Server Directory: Place the hms folder inside your XAMPP htdocs directory.

Database Configuration:

Open phpMyAdmin and create a database named hms_db.

Import the provided hms.sql file into the database.

Access the Application: Open your browser and navigate to http://localhost/hms/index.php.

Project Architecture
The system follows a logical workflow from user login to specialized dashboards (Admin, Doctor, or Patient) and ends with secure session termination.

