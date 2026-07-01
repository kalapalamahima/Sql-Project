# Sql-Project
# Book Management System

## • Project Overview
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

# SQL PROJECT
# DIET MANAGEMENT SYSTEM

## • Project Overview

• The Diet Management System is a relational database project developed using MySQL.

• It is designed to manage users, dietitians, diet plans, meals, and food items efficiently.

• The system helps in organizing nutritional information and tracking diet plans assigned to users.

• The project demonstrates the practical implementation of:
  - Table Creation
  - Primary Keys
  - Foreign Keys
  - Strong and Weak Entities
  - Data Insertion
  - Relationships Between Tables
  - SQL Queries of Different Levels

------------------------------------------------------------

## • Technologies Used

• MySQL

• SQL

------------------------------------------------------------

## • Database Tables

The project contains the following tables:

• Users

• Dietitians

• Diet_Plans

• User_Diet_Plan

• Meals

• Food_Items

------------------------------------------------------------

## • Entity Classification

### Strong Entities

• Users

• Dietitians

• Diet_Plans

### Associative Entity

• User_Diet_Plan

### Weak Entities

• Meals

• Food_Items

------------------------------------------------------------

## • Relationships

• One Dietitian can create multiple Diet Plans (1:N)

• One Diet Plan can contain multiple Meals (1:N)

• One Meal can contain multiple Food Items (1:N)

• Multiple Users can follow the same Diet Plan

• User_Diet_Plan acts as a bridge table between Users and Diet Plans

------------------------------------------------------------

## • SQL Queries Included

### Easy Level Queries

• SELECT

• WHERE

• ORDER BY

• COUNT()

• LIMIT

Examples:

• List all users

• Find a user's email

• Display diet plans below a calorie limit

• Count female users

------------------------------------------------------------

### Intermediate Level Queries

• INNER JOIN

• GROUP BY

• Aggregate Functions

• Date Filtering

Examples:

• Display users with assigned diet plans

• Show dietitians with their plans

• Count food items in meals

• Retrieve users assigned during a specific period

------------------------------------------------------------

### Advanced Level Queries

• Multiple Table JOINS

• GROUP BY

• HAVING

• ORDER BY

• Aggregate Functions

• Subqueries

Examples:

• Most popular diet plan

• Highest calorie diet plan

• User assigned to the highest calorie plan

• Dietitian handling maximum users

------------------------------------------------------------

## • Features

• Proper relational database design

• Use of Primary and Foreign Keys

• Implementation of Strong and Weak Entities

• Data analysis using SQL queries

• ER Diagram representation

• Sample records for testing

• Nutrition and calorie tracking

------------------------------------------------------------

## • Learning Outcomes

Through this project, the following concepts were practiced:

• Database Normalization

• ER Diagram Design

• Primary and Foreign Keys

• Strong and Weak Entities

• One-to-Many Relationships

• Many-to-Many Relationships

• SQL Query Writing

• Aggregate Functions

• Joins and Relational Analysis

• Database Design Principles

------------------------------------------------------------

## • Project Workflow

• Step 1: User registers in the system.

• Step 2: Dietitian creates diet plans based on health goals.

• Step 3: Diet plans are assigned to users.

• Step 4: Each diet plan contains multiple meals.

• Step 5: Each meal contains multiple food items.

• Step 6: Calories and nutritional details are stored.

• Step 7: SQL queries are used to analyze and manage diet information.

------------------------------------------------------------

## • Sample Data

• 10 Users

• 10 Dietitians

• 10 Diet Plans

• 10 User_Diet_Plan Assignments

• 10 Meals

• 10 Food Items

• Total Records: 60

------------------------------------------------------------

## • Concepts Demonstrated

• Relational Database Management System (RDBMS)

• Strong Entities

• Weak Entities

• Primary Keys

• Foreign Keys

• One-to-Many Relationships

• Many-to-Many Relationships

• Aggregate Functions

• SQL Joins

• SQL Constraints

• Data Analysis Using SQL

------------------------------------------------------------

## • Advantages of the System

• Efficient management of diet plans

• Easy tracking of users and nutrition details

• Reduces manual record maintenance

• Supports personalized diet recommendations

• Helps monitor calorie intake

• Provides structured diet information

------------------------------------------------------------

## • Future Enhancements

• BMI Calculation Module

• Daily Progress Tracking

• Diet Recommendation System

• Mobile Application Integration

• User Login and Authentication

• Automated Health Reports

------------------------------------------------------------

## • Author

• Developed as part of SQL Database Practice, DBMS Mini Project, and Academic Learning.

------------------------------------------------------------

## • Project Summary

• The Diet Management System is a MySQL-based relational database project.

• It manages users, dietitians, diet plans, meals, and food items.

• The project demonstrates concepts such as Strong and Weak Entities, Primary and Foreign Keys, Relationships, Joins, Aggregate Functions, and SQL-based Data Analysis.

• It provides an efficient way to organize, assign, and track personalized diet plans and nutritional information.

