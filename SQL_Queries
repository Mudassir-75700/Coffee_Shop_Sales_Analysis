-- Create a new database named 'coffee'
CREATE DATABASE coffee;

-- Select the 'coffee' database to work with
USE coffee;

-- Display all records from the 'coffe_sales' table
SELECT * FROM coffe_sales;

-- Rename the table from 'coffe_sales' to 'coffee_sales'
ALTER TABLE coffe_sales
RENAME TO coffee_sales;

-- Display all records from the renamed 'coffee_sales' table
SELECT * FROM coffee_sales;

-- Display the structure and column details of the 'coffee_sales' table
DESC coffee_sales;

-- Change the 'Date' column data type to DATE
ALTER TABLE coffee_sales
MODIFY COLUMN Date DATE;

-- Convert the date values from DD-MM-YYYY text format into MySQL DATE format
UPDATE coffee_sales
SET Date = STR_TO_DATE(Date, '%d-%m-%Y');

-- Disable MySQL Safe Update Mode to allow UPDATE statements without a key-based WHERE condition
SET SQL_SAFE_UPDATES = 0;

-- Again modify the 'Date' column to ensure it is stored as the DATE data type
ALTER TABLE coffee_sales
MODIFY COLUMN Date DATE;

-- Change the 'Time' column data type to TIME
ALTER TABLE coffee_sales
MODIFY COLUMN Time TIME;

-- Convert time values from HH.MM.SS format into MySQL TIME format
UPDATE coffee_sales
SET Time = STR_TO_DATE(Time, '%H.%i.%S');

-- Again modify the 'Time' column to ensure it is stored as the TIME data type
ALTER TABLE coffee_sales
MODIFY COLUMN Time TIME;


								-- Basic and Intermediate --

-- 1. What is the total revenue generated so far?
SELECT ROUND(SUM(money),2) total_revenue
FROM coffee_sales;

<img width="522" height="197" alt="image" src="https://github.com/user-attachments/assets/2cde2187-b1bb-43d5-99b0-0a7b0895109c" />

































