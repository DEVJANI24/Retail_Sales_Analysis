 🛒 Retail Sales Data Analysis using SQL

This project focuses on analyzing retail sales data using SQL queries. It includes everything from data cleaning and exploration to answering key business questions using structured queries.

---

 📌 Project Objectives

- Design a relational schema for storing sales data.
- Perform data cleaning by identifying and removing NULL values.
- Analyze customer behavior, sales performance, and time-based trends.
- Derive actionable business insights using SQL.

---

🗃️ Database Table: retail_sales

| Column Name      | Data Type    | Description                             |
|------------------|--------------|-----------------------------------------|
| transaction_id   | INT (PK)     | Unique identifier for each transaction  |
| sale_date        | DATE         | Date of the transaction                 |
| sale_time        | TIME         | Time of the transaction                 |
| customer_id      | INT          | Unique customer ID                      |
| gender           | VARCHAR(15)  | Gender of the customer                  |
| age              | INT          | Age of the customer                     |
| category         | VARCHAR(15)  | Product category                        |
| quantity         | INT          | Quantity sold                           |
| price_per_unit   | FLOAT        | Price per unit                          |
| cogs             | FLOAT        | Cost of goods sol
