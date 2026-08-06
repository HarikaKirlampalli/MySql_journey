# MySQL Journey 🚀

Welcome to my MySQL learning journey!

## 📖 About
This repository contains my daily MySQL notes and practice completed during my Codegnan training.

## 📅 Learning Progress

### ✅ Day 1
- Introduction to MySQL
- Database Basics
- MySQL Installation
- SQL Fundamentals

### ✅ Day 2
- DDL Commands
  - CREATE
  - ALTER
  - DROP
  - TRUNCATE
  - RENAME

### ✅ Day 3
- DML Commands
  - INSERT
  - UPDATE
  - DELETE
- WHERE Clause
- Operators

### ✅ Day 4
- Constraints
  - PRIMARY KEY
  - FOREIGN KEY
  - UNIQUE
  - NOT NULL
  - DEFAULT
- Practice Queries

- ## 📅 Day 5 – DML (Data Manipulation Language)

### 📚 Topics Covered
- Introduction to DML
- INSERT Statement
- UPDATE Statement
- DELETE Statement
- TRUNCATE Statement
- DROP Statement

- ### ✅ Day 6
**Topics Covered:**
- AUTO_INCREMENT
- CREATE TABLE AS SELECT (CTAS)
- Backup Table Creation
- Generated (Computed) Columns
- INSERT, UPDATE & DELETE Operations
- User Management
- CREATE USER
- GRANT & REVOKE Privileges
- Access Permission Testing

- ## 📅 Day 7 – TCL, ACID Properties & Locking

📚 Topics Covered:
- Transaction Control Language (TCL)
- Transaction Management
- Local Transactions
- Global Transactions
- ACID Properties
  - Atomicity
  - Consistency
  - Isolation
  - Durability
- COMMIT
- ROLLBACK
- SAVEPOINT
- Locking in MySQL
  - Shared Lock
  - Exclusive Lock
  - Intent Lock

💻 Practical:
- Created `EMPLOYEE` table.
- Performed transactions using `START TRANSACTION`.
- Used `COMMIT` to permanently save changes.
- Used `ROLLBACK` to undo transactions.
- Created and restored `SAVEPOINT`.
- Created `LOCK_DEMO` database.
- Practiced `LOCK TABLES` with `READ` and `WRITE` locks.
- Used `UNLOCK TABLES` to release locks.
- Implemented row-level locking using `SELECT ... FOR UPDATE`.
- Explored real-time examples of ACID properties and database locking.

- ## 📅 Day 8
📚 Topics Covered:
- SQL Constraints
- NOT NULL Constraint
- UNIQUE Constraint
- PRIMARY KEY Constraint
- COMPOSITE KEY
- FOREIGN KEY
- CHECK Constraint
- DEFAULT Constraint
💻 What I Learned:
- Applied different SQL constraints to maintain data integrity.
- Understood the differences between NOT NULL, UNIQUE, and PRIMARY KEY.
- Learned how COMPOSITE KEY uniquely identifies records using multiple columns.
- Explored FOREIGN KEY relationships between parent and child tables.
- Practiced using CHECK and DEFAULT constraints to validate and assign default values.

- ## 📅 Day 9

📚 Topics Covered:
- Comparison Operators (`=`, `!=`, `>`, `<`, `>=`, `<=`)
- Logical Operators (`AND`, `OR`, `NOT`)
- UPDATE with Conditions
- DELETE with Conditions
- Filtering Records using `WHERE`
- Practical SQL Query Practice
💻 Practical:
- Updated product quantity and price using arithmetic operations.
- Performed conditional UPDATE and DELETE queries.
- Practiced comparison operators with `StudentScores` table.
- Applied logical operators (`AND`, `OR`, `NOT`) on `Employees` table.
- Retrieved and modified records using multiple conditions.

- ## 📅 Day 10
📚 Topics Covered:
- Comparison Operators (=, !=, >, <, >=, <=)
- Logical Operators (AND, OR, NOT)
- BETWEEN Operator
- LIKE Operator
- IN Operator
- Conditional Filtering using WHERE
- UPDATE with Conditions
- DELETE with Conditions
- Hands-on Practice Queries

# 📅 Day 11 – MySQL Clauses & Query Execution

## 📖 Topics Covered
- WHERE Clause
- GROUP BY Clause
- HAVING Clause
- ORDER BY Clause (ASC & DESC)
- LIMIT Clause
- Aggregate Functions (COUNT, SUM, AVG, MIN, MAX)
- SQL Query Execution Order

## 💻 Practical Implementation
- Created and populated a `STUDENTS` table.
- Filtered records using `WHERE` with `AND`, `OR`, `IN`, and `BETWEEN`.
- Grouped records using `GROUP BY`.
- Performed calculations using Aggregate Functions.
- Filtered grouped results with `HAVING`.
- Sorted records using `ORDER BY` (Ascending & Descending).
- Retrieved top records using `LIMIT`.
- Practiced SQL Query Execution Order:

- # Day 12 - MySQL Learning Journey 🚀
## Topics Covered:
- GROUP BY
- HAVING
- ORDER BY
- Aggregate Functions
- SET OPERATORS (UNION, UNION ALL, INTERSECT, MINUS)
## Practice:
- Sales Data Analysis Queries
- Student Database Queries
Day 12 Completed ✅

## 📅 Day 13 – MySQL String & Numeric Functions

### Topics Covered
* Numeric Functions (ABS, CEIL, FLOOR, ROUND, MOD, POW, SQRT, LOG, LOG2, LOG10, RADIANS, DEGREES, SIGN, RAND, GREATEST, LEAST, PI, TRUNCATE, BIT_COUNT, OCT, BIN)
* String Functions (CONCAT, CONCAT_WS, UPPER, LOWER, SUBSTRING, SUBSTRING_INDEX, LENGTH, CHAR_LENGTH, REPLACE, TRIM, POSITION, INSTR, LEFT, RIGHT, REVERSE, LPAD, RPAD, ASCII)
* Pattern Matching using `LIKE`
* Real-time Employee Database Practice
* Email Manipulation and String Extraction Queries
### Practice Highlights
* Performed string manipulation using built-in MySQL functions.
* Worked with employee records to perform filtering, formatting, and email processing.
* Practiced real-world SQL interview questions using string functions and pattern matching.

# 📅 Day 14 - MySQL Date & Time Functions

## 📌 Topics Covered
- CURDATE(), CURTIME(), NOW()
- DATE() & TIME()
- YEAR(), MONTH(), DAY(), WEEK(), DAYOFWEEK()
- DATE_ADD() & DATE_SUB()
- DATEDIFF()
- DATE_FORMAT()
- LAST_DAY(), MONTHNAME(), DAYNAME(), QUARTER()
- TIME_TO_SEC() & SEC_TO_TIME()
- SYSDATE()

## 💻 Hands-on Practice
- Created the `employee_attendance` table.
- Inserted employee attendance records with date and time values.
- Extracted date and time from DATETIME columns.
- Retrieved joining year, birth month, birth day, and joining week.
- Added and subtracted dates using `DATE_ADD()` and `DATE_SUB()`.
- Formatted dates using `DATE_FORMAT()`.
- Used functions like `LAST_DAY()`, `MONTHNAME()`, `DAYNAME()`, and `QUARTER()`.
- Converted time to seconds and seconds back to time.
- Solved real-time SQL queries using MySQL Date & Time Functions.

- ## 📅 Day 15 – JOINS & VIEWS
Today, I explored two important MySQL concepts: **JOINS** and **VIEWS**.
### 📚 What I Learned
- Understood why JOINS are used to combine data from multiple tables.
- Learned different types of JOINS:
  - INNER JOIN
  - LEFT JOIN
  - RIGHT JOIN
  - FULL JOIN (using UNION)
  - CROSS JOIN
  - SELF JOIN
- Learned the concept of VIEWS and their advantages.
- Understood how Views simplify complex SQL queries and improve reusability.

## 📅 Day 16 – Sub Queries
Today, I learned one of the most powerful SQL concepts: **Sub Queries**.
### 📚 What I Learned
- Understood what a Sub Query is and why it is used.
- Explored different types of Sub Queries:
  - Single Row Sub Query
  - Multi Row Sub Query (IN)
  - Multi Row Sub Query (ANY / SOME)
  - Multi Row Sub Query (ALL)
  - Nested Sub Query
  - Correlated Sub Query
  - EXISTS & NOT EXISTS

# Day 17 – MySQL Journey 🚀
## 📚 Topics Covered
- Advanced SQL Query Practice
- Nested Subqueries
- Correlated Subqueries
- EXISTS Subqueries
- Aggregate Functions
- Finding 2nd & 3rd Highest/Lowest Salary
- Real-world SQL Queries using World Database
- Stored Procedures
- DELIMITER
- CREATE PROCEDURE
- CALL Statement
- SHOW PROCEDURE STATUS

# 📅 Day 18 – MySQL Stored Procedures & Triggers
Today I learned advanced MySQL concepts by creating and executing Stored Procedures and Triggers.
## 📚 Topics Covered
### ✅ Stored Procedures
- Creating Stored Procedures
- Executing Procedures using CALL
- Viewing Procedures using SHOW PROCEDURE STATUS
- Dropping Procedures
### ✅ Procedure Parameters
- IN Parameter
- OUT Parameter
- INOUT Parameter
### ✅ Procedures Implemented
- Department Wise Employee Count
- Get Employee by ID
- Get Employees by Department
- Employees by Department & Experience
- Salary Range Filter
- Total Employees (OUT Parameter)
- Total IT Employees (OUT Parameter)
- Add Bonus using INOUT Parameter
### ✅ Trigger Concepts
- Introduction to Triggers
- BEFORE INSERT Trigger
- Using NEW keyword
- Validation using SIGNAL SQLSTATE
- Converting Employee Names to UPPERCASE automatically
- Viewing Triggers using SHOW TRIGGERS


---

## 🛠 Tools Used
- MySQL

## 📌 Repository
Daily MySQL notes and practice files will be updated regularly.

## 👩‍💻 Author
**Harika Kirlampalli**
