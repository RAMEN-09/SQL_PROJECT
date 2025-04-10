# SQL_PROJECT
  **E-Commerce MySQL Database**  

A lightweight MySQL solution for online stores, featuring:  

- **Core Tables**: Customers, Products, Orders  
- **Key Analytics**:  
  - Monthly sales reports  
  - Product performance  
  - Customer purchase history  
- **Optimized Queries**: JOINs, subqueries, aggregations  

**Quick Start**:  
```sql
-- Get premium products
SELECT name, price 
FROM products 
WHERE price > (SELECT AVG(price) FROM products);
```

**Business Value**: Track revenue, customers, and inventory in one system.  

[![MySQL](https://img.shields.io/badge/MySQL-8.0+-blue)](https://dev.mysql.com/)  
RAMEN DAS , 2ND YEAR STUDENT.
