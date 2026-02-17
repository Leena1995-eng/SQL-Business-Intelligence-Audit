# SQL-Business-Intelligence-Audit
Relational database analysis using SQL to audit retail operations, join customer/sales tables, and identify high-value geographic segments.

# Retail Operations & Logistics Audit (SQL) 🛒

## 📌 Project Overview
This project demonstrates the use of **SQL (SQLite)** to query a relational database for business insights. I simulated a retail environment with multiple tables to solve complex operational questions regarding revenue, customer behavior, and logistics priority.

## 🔍 SQL Techniques Applied
* **Multi-Table Joins:** Connected `Sales` and `Customers` tables to map revenue to specific geographic regions.
* **Conditional Logic:** Implemented `CASE` statements to automate shipping priority flagging based on order value.
* **Data Cleaning:** Used SQL functions (`UPPER`, `ROUND`) to standardize product names and financial reporting.
* **Aggregations:** Utilized `GROUP BY` and `HAVING` clauses to identify high-performing product categories.

## 🛠️ Tech Stack
* **Database Engine:** SQLite
* **Environment:** Python (used as a bridge for SQL execution)
* **Libraries:** Pandas (for result formatting)

## 📈 Key Query Example
One of the core challenges was identifying "Ghost Customers" (users with zero purchases) to aid marketing re-engagement efforts using a **LEFT JOIN** strategy. See the image
<img width="494" height="134" alt="image" src="https://github.com/user-attachments/assets/1527ea26-fb46-447e-9a01-db7abc496e30" />


<img width="1357" height="225" alt="image" src="https://github.com/user-attachments/assets/03870357-7b16-4c13-a3c6-0a8226f38d31" />
