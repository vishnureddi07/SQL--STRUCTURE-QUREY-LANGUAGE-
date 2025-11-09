 ##  SQL (Structured Query Language) is used to store, manage, and manipulate data in relational databases.
This section covers essential SQL concepts from fundamentals to advanced operations.

🗂️ SQL Command Categories

DDL (Data Definition Language) – Defines and modifies database structures using commands like CREATE, ALTER, and DROP.

DML (Data Manipulation Language) – Manages data inside tables using commands like INSERT, UPDATE, and DELETE.

TCL (Transaction Control Language) – Controls transactions with commands like COMMIT, ROLLBACK, and SAVEPOINT.

DQL (Data Query Language) – Retrieves data from databases using the SELECT statement.

🔑 Keys and Constraints

Primary Key – Uniquely identifies each record in a table (no duplicates, no NULLs).

Foreign Key – Establishes a relationship between two tables for data integrity.

Identity / Seed–Increment – Automatically generates unique values for a column (commonly used with primary keys).

⚙️ SQL Clauses

WHERE Clause – Filters records based on a specific condition.

GROUP BY Clause – Groups rows that have the same values in specified columns.

HAVING Clause – Filters grouped results created by the GROUP BY clause.

ORDER BY Clause – Sorts query results in ascending or descending order.

🧮 Set Operators

UNION – Combines results of two queries and removes duplicates.

UNION ALL – Combines results of two queries including duplicates.

INTERSECT – Returns only common records between two queries.

MINUS / EXCEPT – Returns records from the first query not found in the second.

📊 Ranking Functions

RANK() – Assigns rank to rows, skipping numbers for ties.

DENSE_RANK() – Assigns rank to rows without skipping numbers for ties.

ROW_NUMBER() – Gives a unique sequential number to each row in a result set.

🧩 Data Types and Differences

CHAR – Fixed-length character data type (always occupies defined length).

VARCHAR – Variable-length character data type (uses only needed space).

INT / FLOAT / DECIMAL – Used for numeric data with different precision and storage.

DATE / DATETIME – Used for storing date and time information.

🧠 MySQL Database

MySQL – An open-source relational database management system widely used for web and enterprise applications.

Supports ACID properties, stored procedures, views, triggers, and indexes for efficient data handling.
