# Sql-Project
 Bookstore Management System

 Project Overview
The Bookstore Management System is a relational database project developed using MySQL.  
This project is designed to manage bookstore operations such as maintaining books, authors, genres, customers, orders, and order details.

The database demonstrates the implementation of:
- Table creation
- Primary and foreign keys
- Data insertion
- Relationships between tables
- SQL queries of different difficulty levels

---

 Technologies Used
- MySQL
- SQL

---

 Database Tables
The project contains the following tables:

1. Authors
2. Genres
3. Customers
4. Books
5. Orders
6. Order_Details

---

 Relationships
- One author can write multiple books
- One genre can contain multiple books
- One customer can place multiple orders
- One order can contain multiple books

---

 SQL Queries Included

 Easy Level Queries
Queries using:
- WHERE clause
- Operators
- BETWEEN
- LIKE

 Intermediate Level Queries
Queries using:
- Aggregate Functions
- AVG()
- MAX()
- COUNT()
- SUM()
- GROUP BY

 Hard Level Queries
Queries using:
- JOINS
- GROUP BY
- HAVING
- ORDER BY

---

 Features
- Proper relational database design
- Use of primary and foreign keys
- Data analysis using SQL queries
- ER Diagram included
- Sample records inserted for testing

---

 Learning Outcomes
Through this project, the following concepts were practiced:
- Database normalization
- SQL query writing
- Table relationships
- Aggregate functions
- Joins and relational analysis
- ER diagram design

---

 Author
Developed as part of SQL database practice and academic learning.

=============================================================================================================================

Diet Management System
Project Overview

The Diet Management System is a relational database project developed using MySQL.

This project is designed to manage diet planning activities such as maintaining user information, dietitians, diet plans, meals, food items, and diet plan assignments.

The database demonstrates the implementation of:

Table creation
Primary and foreign keys
Strong and weak entities
Data insertion
Relationships between tables
SQL queries of different difficulty levels
Technologies Used
MySQL
SQL
Database Tables

The project contains the following tables:

Users
Dietitians
Diet_Plans
User_Diet_Plan
Meals
Food_Items
Entity Classification
Strong Entities
Users
Dietitians
Diet_Plans
Associative Entity
User_Diet_Plan
Weak Entities
Meals
Food_Items
Relationships
One Dietitian can create multiple Diet Plans (1:N)
One Diet Plan can contain multiple Meals (1:N)
One Meal can contain multiple Food Items (1:N)
One User can be assigned a Diet Plan
Multiple Users can follow the same Diet Plan
User_Diet_Plan acts as a bridge table between Users and Diet Plans
SQL Queries Included
Easy Level Queries

Queries using:

SELECT
WHERE clause
ORDER BY
COUNT()
LIMIT

Examples:

List all users
Find a user's email
Display diet plans below a calorie limit
Count female users
Intermediate Level Queries

Queries using:

INNER JOIN
GROUP BY
Aggregate Functions
Date Filtering

Examples:

Display users with assigned diet plans
Show dietitians with their plans
Count food items in meals
Retrieve January assignments
Hard Level Queries

Queries using:

Multiple Table JOINS
GROUP BY
HAVING
ORDER BY
Aggregate Functions
Subqueries

Examples:

Most popular diet plan
Highest calorie diet plan
User assigned to highest calorie plan
Dietitian managing maximum users
Features
Proper relational database design
Use of primary and foreign keys
Strong and weak entity implementation
Data analysis using SQL queries
ER Diagram included
Sample records inserted for testing
Supports diet planning and nutrition tracking
Learning Outcomes

Through this project, the following concepts were practiced:

Database normalization
ER Diagram design
Strong and Weak Entities
Primary and Foreign Keys
Table relationships
SQL query writing
Aggregate functions
Joins and relational analysis
Database design principles
Project Workflow
Users register in the system.
Dietitians create diet plans based on nutritional goals.
Diet plans are assigned to users.
Each diet plan contains multiple meals.
Each meal contains multiple food items.
The system tracks calories and meal information.
SQL queries are used to analyze user diets and plan effectiveness.
Sample Data

The project contains:

10 Users
10 Dietitians
10 Diet Plans
10 User_Diet_Plan Assignments
10 Meals
10 Food Items

Total Records: 60

Learning Concepts Demonstrated
Relational Database Management System (RDBMS)
One-to-Many Relationships
Many-to-Many Relationships (through bridge table)
Strong and Weak Entities
SQL Constraints
Aggregate Functions
Joins
Grouping and Filtering
Database Query Optimization Basics

Author
Developed as part of SQL Database Practice, DBMS Mini Project, and Academic Learning.


