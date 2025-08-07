# SQL-Based Product Sales Analysis using Chinook Database

This project is part of my internship task focused on analyzing product (music track) sales using SQL. The analysis is done on the **Chinook Database**, a sample music store database containing tables for customers, invoices, tracks, artists, and more.

---

## Objectives

The goal of this project is to answer key business questions using SQL:

- Identify **top-selling products (tracks)**
- Analyze **revenue by country/region**
- Evaluate **monthly sales performance**
- Bonus: Use a **window function** to find the top-selling track per month

---

## Dataset: Chinook Database

- Source: [Chinook Database Kaggle]
- Format used: `Chinook_Sqlite.sqlite`
- Loaded via: [SQLiteOnline](https://sqliteonline.com)

---

## 🧠 Key SQL Concepts Used

- `JOIN`: To combine product, sales, and customer information
- `GROUP BY`: To group results (by track, country, month)
- `SUM()`: To calculate revenue and quantity
- `ORDER BY`: To sort results
- `LIMIT`: To show top results
- `SUBSTR()`: To extract month from invoice date
- `RANK() OVER (PARTITION BY ...)`: To rank top products per month (bonus)

---
