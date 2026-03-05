# Online Bookstore Database Project (SQL + PostgreSQL)

This project demonstrates the design of a relational database for an online bookstore and the use of SQL queries to perform data analysis using PostgreSQL.


## Database Schema

The database consists of three main tables:

1. **Books**
2. **Customers**
3. **Orders**

The Orders table references both Books and Customers using foreign keys.

## Files in this Repository

* **schema.sql** → Database structure (tables and relationships)
* **queries.sql** → SQL queries used for data analysis
* **Books.csv** → Dataset for books
* **Customers.csv** → Dataset for customers
* **Orders.csv** → Dataset for orders

## SQL Concepts Used

* SELECT
* WHERE
* JOIN
* GROUP BY
* HAVING
* Aggregate Functions (SUM, COUNT, AVG)
* COALESCE
* Foreign Keys

## Example Analysis

* Find total revenue from orders
* Identify most popular books
* Calculate remaining stock
* Identify customers with multiple orders

## Tools Used

* PostgreSQL
* SQL
* pgAdmin

