MySQL Assignment 1 – DDL Commands & Constraints

This repository contains the SQL solutions for MySQL Assignment 1, focusing on Data Definition Language (DDL) commands and database constraints using an Employee Management schema.

📊 Database Schema
The database (employee) consists of three main tables:

departments: Stores department details (department_id, department_name).

location: Stores office locations (location_id, location).

employees: Stores employee records (employee_id, employee_name, gender, age, hire_date, designation, department_id, location_id, salary).


DDL Commands Used

CREATE: Creating the employee database 

ALTER: Adding (email), modifying (designation), dropping (age), and renaming (hire_date to date_of_joining) columns.

RENAME: Renaming departments to Departments_Info and location to Locations.

TRUNCATE: Clearing all records from the employees table while keeping its structure intact.

DROP: Deleting the employees table and the employee database.


Database Constraints

PRIMARY KEY & AUTO_INCREMENT: Ensuring unique record identification and automatic sequential numbering for locations.

NOT NULL & UNIQUE: Preventing empty or duplicate values 

ENUM & CHECK: Validating data integrity (restricting gender to 'M' or 'F', and ensuring age >= 18).

DEFAULT: Automatically assigning the current system date to hire_date when omitted.

FOREIGN KEY: Establishing relational links between employees, departments, and location.



How to Run

Open MySQL Workbench

Copy the SQL queries from the solution script.

Execute the queries step-by-step to observe how the schema evolves through DDL operations and constraint enforcement.
