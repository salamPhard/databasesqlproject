# databasesqlproject
A library management system database schema

Use Case: Library Management System
Entities:

Books

Authors

Members

Loans

Categories

Relationships:

A book can have multiple authors (M:N)

A book belongs to one category (1:M)

A member can borrow multiple books (1:M)

A loan links a member to a book

Each loan has a loan date and return date
