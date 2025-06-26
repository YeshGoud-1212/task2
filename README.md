# Task 2 - Data Insertion and Handling Nulls

## 🎯 Objective
This task focuses on practicing SQL Data Manipulation Language (DML) operations such as `INSERT`, `UPDATE`, and `DELETE`, along with handling `NULL` values and default constraints.

---

## 📂 Files Included

| File Name      | Description                                   |
|----------------|-----------------------------------------------|
| `insert.sql`   | SQL statements to insert data into a sample table, including handling of NULLs and default values |
| `update.sql`   | SQL to update records based on conditions     |
| `delete.sql`   | SQL to delete specific rows using WHERE clause |

---

## 🛠 Key Concepts Used

- `INSERT INTO` with all and partial columns
- Handling `NULL` values
- Using `DEFAULT` values
- `UPDATE` with `WHERE`
- `DELETE` with `WHERE`
- `IS NULL` condition
- `ON DELETE CASCADE` (if foreign key is used)

---

## 🧪 Sample Table Structure Used

```sql
CREATE TABLE employees (
  emp_id INTEGER PRIMARY KEY,
  name TEXT NOT NULL,
  department TEXT,
  salary INTEGER DEFAULT 30000,
  email TEXT UNIQUE
);
