# Library Management System

## Description
This project is a **Library Management System** designed to manage books, authors, categories, members, and loans in a library. It provides a relational database schema to store and manage data efficiently. The schema includes tables for categories, authors, books, members, and loans, as well as a many-to-many relationship between books and authors.

## How to Run/Setup the Project
1. Install a database management system (DBMS) such as MySQL or MariaDB.
2. Open your DBMS client or command-line interface.
3. Import the SQL schema:
   - If using a GUI client, open the `Database_finals.sql` file and execute it.
   - If using the command line, run the following command:
     ```bash
     mysql -u [username] -p [database_name] < c:\Users\ADMIN\Desktop\sql\Database_finals.sql
     ```
4. The database schema will be created with the following tables:
   - `Categories`
   - `Authors`
   - `Books`
   - `Book_Author`
   - `Members`
   - `Loans`

## Screenshot of ERD
**Entity-Relationship Diagram (ERD) file  for the Library Management System is on the repository**


## Features
- Categorization of books.
- Management of authors and their books.
- Tracking of library members and their loan history.
- Support for many-to-many relationships between books and authors.
  
