# SQL-Data-Analytics-BookStore

This is a SQL-only data analytics project built in MySQL Workbench.
It simulates an Online Bookstore where I imported CSV datasets into MySQL tables and wrote 20+ SQL queries (basic & advanced) to extract business insights.

The focus of this project is on data analysis using SQL — querying, aggregations, joins, grouping, and insights.

## Data Sets of this Project

The project uses three CSV datasets (included in the data/ folder):

Books.csv → Book_ID, Title, Author, Genre, Published_Year, Price, Stock

Customers.csv → Customer_ID, Name, Email, Phone, City, Country

Orders.csv → Order_ID, Customer_ID, Book_ID, Order_Date, Quantity, Total_Amount

These files were imported into MySQL using LOAD DATA INFILE.

## Queries

14 Basic Queries — filtering, aggregation, grouping, ordering
8 Advanced Queries — joins, group aggregates, HAVING, subqueries, top-N queries
