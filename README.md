### SQL Overview

**SQL (Structured Query Language)** is a domain-specific language used to manage and manipulate relational databases. It is the most common language for querying and interacting with data in databases, such as retrieving, inserting, updating, and deleting data. SQL works with **Relational Database Management Systems (RDBMS)**, which organize data into tables with rows and columns.

### Key Concepts in SQL

1.  **Database**: A structured collection of data. In SQL, databases store data in **tables** (also called relations), each with a set of **columns** (fields) and **rows** (records).
2.  **Tables**: Tables store data in a grid format, where each row is a single record, and each column represents a property of that record. Each column has a specific **data type**.

### SQL Commands: C.R.U.D.

SQL operations can be broken down into four basic categories known as **C.R.U.D**:

*   **C** - **Create**: Adding new records to the database (`INSERT` statement).
*   **R** - **Read**: Retrieving data from the database (`SELECT` statement).
*   **U** - **Update**: Modifying existing records in the database (`UPDATE` statement).
*   **D** - **Delete**: Removing records from the database (`DELETE` statement).

### Common SQL Statements

*   `CREATE TABLE`: Used to create a new table.
*   `INSERT INTO`: Inserts new records into a table.
*   `SELECT`: Retrieves data from a table.
*   `UPDATE`: Updates existing data in a table.
*   `DELETE`: Removes data from a table.
*   `DROP TABLE`: Deletes a table from the database.

### SQL Data Types

Data types specify the kind of data that can be stored in a column. Common SQL data types include:

*   **INT**: Integer (whole numbers).
*   **VARCHAR**: Variable-length character string (used for text).
*   **DATE**: Stores date values.
*   **BOOLEAN**: Stores `TRUE` or `FALSE` values.
*   **FLOAT**: Stores decimal numbers.

### A.C.I.D Properties

In SQL databases, the term **ACID** stands for the four key properties that guarantee reliable transactions:

*   **A** - **Atomicity**: Each transaction is all-or-nothing. If one part fails, the entire transaction fails.
*   **C** - **Consistency**: A transaction must bring the database from one valid state to another, ensuring the data meets all validation rules.
*   **I** - **Isolation**: Transactions occur independently, ensuring that concurrent transactions don’t interfere with each other.
*   **D** - **Durability**: Once a transaction is committed, it will remain so, even in the event of a system failure.

### SQL Relationships

In a relational database, tables can be related to each other using **foreign keys**:

*   **Primary Key**: A unique identifier for each record in a table.
*   **Foreign Key**: A field that references the primary key in another table, creating a relationship between the two tables.

### Normalization

Normalization is the process of organizing data to reduce redundancy and dependency. Data is broken down into smaller, related tables, each with a clear purpose.

### Indexes

Indexes are used to speed up the retrieval of data. They are created on columns that are frequently used in queries to make search operations faster.

### Joins

**Joins** combine rows from two or more tables based on a related column between them:

*   **INNER JOIN**: Returns only matching rows between tables.
*   **LEFT JOIN**: Returns all rows from the left table and matching rows from the right.
*   **RIGHT JOIN**: Returns all rows from the right table and matching rows from the left.
*   **FULL JOIN**: Returns all rows from both tables.

### Fun Facts About SQL

*   SQL was developed by IBM in the 1970s.
*   SQL is **declarative**, meaning you specify what you want, not how to do it.
*   Almost every major database system (MySQL, PostgreSQL, SQLite, Oracle) uses SQL, though there are slight variations (called **dialects**).
*   SQL is highly readable and resembles English in its structure, which makes it easy to learn and use.

### How to Explain SQL to a Classmate

"SQL is like a language that helps you communicate with a database. Imagine the database is a library, and SQL is the librarian. You tell the librarian (SQL) what book you want (data), and they fetch it for you. With SQL, you can add new books (insert), find books (select), update the details of a book (update), or remove books (delete). It's organized and reliable thanks to the **ACID** rules that keep things running smoothly, and **CRUD** is just the actions you take—Create, Read, Update, and Delete!"

