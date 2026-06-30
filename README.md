# AttendanceSQL
    Teacher attendance management system built with PHP, SQLite, Bootstrap, and JavaScript.
NSUT Teacher Attendance Portal

A lightweight attendance management system built using PHP, SQLite, Bootstrap, HTML, CSS, and JavaScript. The application enables teachers to mark attendance and students to view attendance statistics through separate dashboards.

Features

* Teacher login and student login
* Teacher dashboard for marking attendance by subject and date
* Student dashboard to view attendance records and percentage
* Responsive Bootstrap-based user interface
* SQLite database with pre-populated mock data
* Secure database interaction using PDO prepared statements

Tech Stack

* Frontend: HTML, CSS, Bootstrap 5, JavaScript
* Backend: PHP
* Database: SQLite
* Database Access: PDO

Project Structure

attendancesql/
├── api/
├── config.php
├── database.sql
├── index.php
├── init_database.php
├── student_dashboard.php
├── teacher_dashboard.php
└── README.md

Getting Started

Prerequisites

* PHP 7.4+
* PDO SQLite extension enabled

Installation

Clone the repository:

git clone <repository-url>
cd attendancesql

Initialize the database:

php init_database.php

Start the PHP server:

php -S localhost:8000

Open your browser:

http://localhost:8000

SQL Concepts Demonstrated

* CREATE TABLE
* INSERT
* SELECT
* UPDATE
* DELETE
* JOIN & LEFT JOIN
* GROUP BY
* Aggregate Functions
* CASE Statements
* Transactions
* Views
* Prepared Statements using PDO

Database Tables

* Students
* Teachers
* Subjects
* Subject Teacher Mapping
* Attendance

Screenshots

Add screenshots of the login page, teacher dashboard, and student dashboard here.

License

This project was developed for educational purposes.
