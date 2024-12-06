# database management system

This project demonstrates the creation and management of a relational database system for a business setting. The database includes three main tables: Customers, Products, and Orders, which interact with one another to store and retrieve essential business information. The project involves creating the tables, populating them with data, and performing queries to derive insights.

# Table Creation

customer table Stores details about customers, including their location, region, and preferred product.
product table Contains information on products, including their category, sales, quantity, discount, and profit.
orders table Tracks order details like order ID, order date, shipping mode, and shipping date.
Relationships

A relationship exists between customer and product tables, where a customer can purchase multiple products.
The orders table connects to products via a foreign key, allowing the tracking of sales.

# Data Operations

i have populated the database with sample data using INSERT statements.
Established relationships between the tables using foreign keys with ON DELETE SET NULL constraints.
