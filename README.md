# 🛒 Ecommerce-SQL-Analysis
This project analyzes the operations of an online marketplace in Brazil using SQL only. It covers various aspects of e-commerce including customer behavior, delivery timelines, freight cost, payment methods, and regional performance.

---

## 📌 Objective

To derive actionable insights from structured relational data using only SQL. The project aims to:

- Identify seasonal shopping trends and peak months
- Measure delivery performance across states
- Understand customer distribution and payment behavior
- Track freight costs and their economic impact

---

## 🗂️ Datasets Used

- `customers`, `orders`, `order_items`, `payments`, `order_reviews`, `products`, `sellers`, `geolocation`

These tables include over 100,000 records with timestamps, locations, and transaction data.

---

## 🛠 Tools & Technologies

- **MySQL / BigQuery**
- Analytical SQL (joins, date functions, aggregations, filtering)

---

## 🔍 Key Analyses Performed

### 1. 📆 Time Period & Structure
- Verified column data types
- Assessed data availability between 2016–2018

### 2. 🛍️ Customer & Order Trends
- Month-on-month growth in orders
- Purchase hours categorized (Morning, Afternoon, Night)
- Top cities and states by customer volume

### 3. 📦 Delivery & Freight
- Calculated actual vs estimated delivery delays
- Average freight value and time-to-delivery per state
- Ranked states with best and worst delivery performance

### 4. 💰 Payment Behavior
- Most common payment types over time
- Analysis of payment installments across orders

### 5. 📈 Economic Impact
- % increase in payment values (2017 vs 2018)
- Regional contribution to gross e-commerce value

---

## 📊 Sample Query Types

- `JOIN`, `GROUP BY`, `ORDER BY`, `DATE_DIFF`, `ROUND`, `AVG`, `LIMIT`
- Aggregations on customer behavior and regional delivery trends

---

## 👤 Author

**Popatsing Waghela**  
Data Analyst (Finance Background)  \  
[LinkedIn](https://www.linkedin.com/in/popatsing-waghela-3b7a87246) | [GitHub](https://github.com/Waghela007)


---

_This project demonstrates business understanding, operational analytics, and SQL proficiency using a real e-commerce database._
