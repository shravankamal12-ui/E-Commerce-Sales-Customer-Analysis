# E-Commerce Sales & Customer Analysis

##  Project Objective

This project analyzes e-commerce sales and customer data using **MySQL**.

The main objectives are to:

* Analyze total sales and orders.
* Identify top customers and products.
* Analyze sales by category, city, state, and payment method.
* Understand customer purchasing patterns.
* Generate useful business insights using SQL.

##  Database Structure

The project contains four relational tables:

### 1. Customers

Stores customer information such as:

* Customer ID
* Customer Name
* Email
* City
* State
* Registration Date

### 2. Products

Stores product information such as:

* Product ID
* Product Name
* Category
* Price
* Stock Quantity

### 3. Orders

Stores order information such as:

* Order ID
* Customer ID
* Order Date
* Total Amount
* Payment Method
* Order Status

### 4. Order_Items

Stores individual products included in each order:

* Order Item ID
* Order ID
* Product ID
* Quantity
* Unit Price

### 🔗 Relationships

**Customers → Orders → Order_Items ← Products**

Primary keys and foreign keys are used to maintain relationships between the tables.

## 🛠️ SQL Concepts Used

* Database and table creation
* Primary Keys
* Foreign Keys
* INSERT statements
* SELECT statements
* WHERE conditions
* INNER JOIN
* GROUP BY
* ORDER BY
* Aggregate Functions

  * `SUM()`
  * `COUNT()`
  * `AVG()`
  * `MAX()`
  * `MIN()`
* Subqueries
* `UNION ALL`
* Sorting and filtering
* Business-oriented data analysis

##  Key Results

| Metric                    |                  Result |
| ------------------------- | ----------------------: |
| Total Sales               |               ₹1,87,100 |
| Total Orders              |                      15 |
| Total Customers           |                      10 |
| Total Products            |                      10 |
| Total Order Items         |                      16 |
| Average Order Value       |              ₹12,473.33 |
| Average Customer Spending |                 ₹18,710 |
| Highest Order             |                 ₹55,000 |
| Top Customer              |  Rahul Sharma — ₹58,200 |
| Top Product by Revenue    |    Smartphone — ₹75,000 |
| Top Category              | Electronics — ₹1,55,400 |
| Top City                  |     Bengaluru — ₹69,900 |
| Top State by Revenue      |   Karnataka — ₹1,01,900 |
| Most Used Payment Method  |          UPI — 8 orders |
| Delivered Orders          |                      15 |

##  Project Insights

* **Electronics** generated the highest category revenue.
* **Smartphone** generated the highest product revenue.
* **Rahul Sharma** was the highest-spending customer.
* **Karnataka** generated the highest state revenue.
* **Bengaluru** generated the highest city revenue.
* **UPI** was the most frequently used payment method.
* All **15 orders** in the dataset were delivered.
* The inventory value of available products was **₹34,15,000**.

##  Conclusion

This project demonstrates how SQL can be used to transform raw e-commerce data into meaningful business insights.

The analysis can help businesses understand customer behavior, identify high-performing products and categories, evaluate sales performance, and support data-driven decision-making.

##  Technology Used

**MySQL 8.0**

**MySQL Workbench 8.0 CE**
