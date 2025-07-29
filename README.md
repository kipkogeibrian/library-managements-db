# Library Management System Database

A complete relational database for managing library operations including books, members, loans, and fines.

## Features

- Tracks books, authors, and publishers
- Manages library members and their loans
- Handles book categorization
- Processes fines for overdue books
- Includes views and stored procedures for common operations

## Database Schema

The database consists of 10 tables with proper relationships:

1. **Members** - Library members
2. **Authors** - Book authors
3. **Publishers** - Book publishers
4. **Books** - Book inventory
5. **Book_Authors** - Many-to-many relationship
6. **Categories** - Book categories
7. **Book_Categories** - Many-to-many relationship
8. **Loans** - Book checkout records
9. **Fines** - Overdue fines
10. **Staff** - Library staff

## Setup Instructions

1. Clone this repository
2. Import the SQL file into your MySQL server:
   ```bash
   mysql -u username -p < library_management.sql
