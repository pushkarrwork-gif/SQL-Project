# University Database Management System

## Overview

This project is a comprehensive **University Database Management System** designed to efficiently store, manage, and retrieve academic records. Built using SQL and tested in MySQL Workbench, the database handles crucial information regarding students, professors, departments, and course enrollments.

As a data project, it demonstrates the ability to design relational schemas and write complex SQL queries to extract meaningful insights from structured data.

## Key Features

* **Student Management:** Tracks student details, including demographics and academic standing.

* **Faculty Records:** Manages professor profiles and their departmental affiliations.

* **Department Administration:** Organizes university departments and their respective heads/budgets.

* **Enrollment Tracking:** Maps students to their enrolled courses and the professors teaching them, facilitating academic record-keeping.

## Technologies Used

* **Language:** SQL (Structured Query Language)

* **Database Management System (DBMS):** MySQL

* **Environment:** MySQL Workbench

## SQL Concepts Applied

This project heavily utilizes advanced SQL concepts to ensure data integrity and facilitate deep analysis:

* **DDL & DML:** Standard data definition (CREATE, ALTER) and manipulation (INSERT, UPDATE, DELETE).

* **Joins:** Extensive use of `INNER JOIN`, `LEFT JOIN`, and `RIGHT JOIN` to connect normalized tables (e.g., linking a student's ID to their department details).

* **Clauses:** Filtering and grouping data using `WHERE`, `GROUP BY`, `HAVING`, and `ORDER BY` for aggregate reporting.

* **Subqueries:** Implementing nested queries to solve complex data retrieval scenarios (e.g., finding students enrolled in more than the average number of courses).

## Database Schema (Entities)

<img width="940" height="436" alt="image" src="https://github.com/user-attachments/assets/9f2475f8-49bf-4ad5-a810-064839c0ea15" />


## Getting Started

### Prerequisites

* Install [MySQL Server](https://dev.mysql.com/downloads/mysql/)

* Install [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

### Installation

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/yourusername/university-dbms.git
   
   ```

2. Open **MySQL Workbench** and connect to your local server.

3. Open the `University Management System Database.sql` file provided in this repository.

4. Execute the script to create the database, build the tables, and insert the sample data.

## Author

* **\[Pushkar Patil\]** - *Data Analyst*

*Feel free to reach out or connect with me on LinkedIn if you have any questions about this project!*
