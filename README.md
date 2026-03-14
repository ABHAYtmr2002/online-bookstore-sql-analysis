# Online Bookstore SQL Analysis (PostgreSQL)

## Project Overview

This project demonstrates SQL data analysis using PostgreSQL on an Online Bookstore dataset.  
The database contains information about books, customers, and orders placed in the bookstore.

Using SQL queries, the project analyzes sales performance, customer purchasing behavior, and inventory management.

---

## Database Schema

The database consists of three tables:

### 1. Books
Stores information about books available in the bookstore.

Columns:
- Book_ID
- Title
- Author
- Genre
- Published_Year
- Price
- Stock

### 2. Customers
Stores customer information.

Columns:
- Customer_ID
- Name
- Email
- Phone
- City
- Country

### 3. Orders
Stores order details for purchased books.

Columns:
- Order_ID
- Customer_ID
- Book_ID
- Order_Date
- Quantity
- Total_Amount

### Table Relationships

Customers place Orders  
Orders contain Books

---

## Technologies Used

- PostgreSQL
- SQL
- pgAdmin

---

## SQL Concepts Used

This project demonstrates the use of important SQL concepts including:

- SELECT
- WHERE
- JOIN
- GROUP BY
- HAVING
- ORDER BY
- LIMIT
- DISTINCT
- Aggregate Functions (SUM, AVG, COUNT)
- LEFT JOIN
- COALESCE

---

## Business Questions Solved

### Basic SQL Queries

1. Retrieve all books in the **Fiction** genre.
2. Find books **published after the year 1950**.
3. List all customers from **Canada**.
4. Show orders placed in **November 2023**.
5. Retrieve the **total stock of books available**.
6. Find the **most expensive book**.
7. Show orders where **more than one quantity** of a book was ordered.
8. Retrieve orders where the **total amount exceeds $20**.
9. List all **unique genres** available in the bookstore.
10. Find the book with the **lowest stock**.
11. Calculate the **total revenue generated from all orders**.
12. Retrieve the **total number of books sold for each genre**.
13. Find the **average price of books in the Fantasy genre**.
14. List customers who have placed **at least 2 orders**.
15. Find the **most frequently ordered book**.
16. Show the **top 3 most expensive Fantasy books**.
17. Retrieve the **total quantity of books sold by each author**.
18. List the **cities where customers spent more than $30**.
19. Find the **customer who spent the most on orders**.
20. Calculate the **remaining stock after fulfilling all orders**.

---

## Dataset Files

The dataset used in this project includes:

- Books.csv
- Customers.csv
- Orders.csv

---

## Project Structure
