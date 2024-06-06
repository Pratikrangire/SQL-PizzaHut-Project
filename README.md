# SQL-PizzaHut-Project

## Description

The Pizza Hut SQL Project is designed to manage and analyze data for a fictional Pizza Hut franchise. This project includes SQL scripts to create and populate a database, perform queries to retrieve meaningful insights, and handle typical business operations such as order management, inventory tracking, and customer relationship management.


## Project Structure

- sql: Contains SQL scripts for creating tables, inserting data, and running queries.
- data: CSV files with sample data for each table.
- analysis: SQL scripts for different types of data analysis.

## Tables

1. **order_details**
   - order_id (INT, Foreign Key)
   - pizza_i (INT, Foreign Key)
   - quantity (INT)
   - price (DECIMAL)

2. **orders**
   -  rder_i (INT, Primary Key)
   - customer_id (INT)
   - order_date (DATE)
   - total_amount (DECIMAL)

3. **pizzas_types**
   - pizza_id (INT, Primary Key)
   - pizza_name (VARCHAR)
   - category (VARCHAR)

4. **pizzas**
   - pizza_id (INT, Primary Key)
   - pizza_type_id (INT, Foreign Key)
   - size (VARCHAR)
   - price (DECIMAL)
