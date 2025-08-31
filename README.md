# 📚 Online Bookstore SQL Project

---

## ✨ Overview
The **Online Bookstore SQL Project** is a relational database system designed to manage:
- 📖 **Books** inventory  
- 👤 **Customers** information  
- 🛒 **Orders** and transactions  

This project includes:
✔ **Database schema creation**  
✔ **Basic & advanced SQL queries**  
✔ **Data analysis for revenue, stock, and customer insights**  

---

## 📂 Project Structure
├── .gitignore # Ignored files for Git
├── Books.csv # Sample Books data
├── Customers.csv # Sample Customers data
├── Orders.csv # Sample Orders data
├── sql project.sql # Schema + Queries
└── README.md # Project Documentation

yaml
Copy code

---

## 🚀 Features
✅ Create and manage **Books**, **Customers**, and **Orders** tables  
✅ Perform **CRUD operations** and analytical queries  
✅ Calculate **total revenue**, **top customers**, and **best-selling books**  
✅ Track **stock availability** after orders  

---

## 🛠 Tech Stack
- **Database:** PostgreSQL (MySQL compatible)
- **Query Language:** SQL
- **Sample Data:** CSV files

---

## ▶️ How to Run
1. **Create a PostgreSQL Database**.
2. **Run `sql project.sql`** to create tables and add queries.
3. (Optional) **Import CSV files** into tables:
   - `Books.csv` → **Books**
   - `Customers.csv` → **Customers**
   - `Orders.csv` → **Orders**
4. Execute queries for insights and reports.

---

## 🔍 Sample Queries
**1. Get all Fiction books:**
```sql
SELECT * FROM Books WHERE Genre = 'Fiction';
2. Calculate total revenue:

sql
Copy code
SELECT SUM(Total_Amount) AS Revenue FROM Orders;
3. Find top 3 most expensive Fantasy books:

sql
Copy code
SELECT Title, Price FROM Books WHERE Genre = 'Fantasy' ORDER BY Price DESC LIMIT 3;
📜 License
Licensed under the MIT License – Free to use and modify.

