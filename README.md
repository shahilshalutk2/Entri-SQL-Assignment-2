# MySQL Assignment 2: Querying Data

A comprehensive SQL assignment demonstrating data retrieval, filtering, aggregation, grouping, and relational joins using MySQL.

---

## 📌 Database Schema Overview

The database comprises three relational tables: `departments`, `location`, and `employees`.

```sql
-- Departments Table
CREATE TABLE departments (
    department_id INT PRIMARY KEY,
    department_name VARCHAR(100) NOT NULL UNIQUE
);

-- Locations Table
CREATE