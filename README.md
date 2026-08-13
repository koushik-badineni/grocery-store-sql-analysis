# 🛒 Grocery Store Management & SQL Data Analysis

A SQL-based grocery store management and business analytics project designed to analyze customer purchasing behavior, product performance, sales trends, supplier contribution, and employee performance using a relational database.

---

## 📌 Project Overview

This project focuses on designing and analyzing a relational database for a grocery store using SQL.

The database stores information about:

- Customers
- Products
- Categories
- Suppliers
- Employees
- Orders
- Order Details

SQL queries are used to extract business insights, analyze sales performance, understand customer purchasing behavior, evaluate supplier contributions, and compare employee performance.

The project demonstrates practical SQL concepts and their application to real-world business problems.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Design and analyze a relational grocery store database.
2. Understand customer purchasing behavior.
3. Analyze product performance and revenue.
4. Identify sales and order trends.
5. Evaluate supplier contribution.
6. Analyze employee performance.
7. Perform detailed order-level analysis.
8. Generate business reports using SQL.
9. Apply SQL concepts to solve real-world business problems.
10. Generate insights that can support business decision-making.

The project specifically applies SQL concepts including **JOINs, aggregate functions, subqueries, window functions, GROUP BY, HAVING, and date functions**. :contentReference[oaicite:1]{index=1}

---

## 🛠️ Technologies Used

- MySQL
- SQL
- Relational Database Management System (RDBMS)

### SQL Concepts Used

- CREATE DATABASE
- CREATE TABLE
- PRIMARY KEY
- FOREIGN KEY
- JOIN
- INNER JOIN
- GROUP BY
- ORDER BY
- HAVING
- Aggregate Functions
- Subqueries
- Window Functions
- Date Functions
- CASE Statements
- STR_TO_DATE()
- YEAR()
- MONTH()
- DAYOFWEEK()
- LIMIT

---

## 🗄️ Database Schema

The database contains the following tables:

```text
Supplier
    ↓
Products ← Categories
    ↓
Order Details
    ↓
Orders ← Customers
    ↓
Employees
