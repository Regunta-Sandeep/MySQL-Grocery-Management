# GM Store Database Project

This project contains a SQL database schema and sample data for a store management system called GM. It includes tables for managing suppliers, product categories, employees, customers, products, orders, and order details.

## Project Structure

- `GM Schema.sql` - The main database schema file containing table definitions and sample analytical queries
- `Categories.csv` - Sample data for product categories
- `Customers.csv` - Sample customer data
- `OrderDetails.csv` - Sample order details data
- `Orders.csv` - Sample order data
- `Products.csv` - Sample product data
- `Store_Employees.csv` - Sample employee data
- `Suppliers.csv` - Sample supplier data

## Database Schema

The database consists of the following tables:

1. **supplier** - Stores supplier information (ID, name, address)
2. **categories** - Product categories (ID, name)
3. **employees** - Store employees (ID, name, hire date)
4. **customers** - Customer information (ID, name, address)
5. **products** - Product catalog (ID, name, supplier, category, price)
6. **orders** - Order records (ID, customer, employee, date)
7. **order_details** - Order line items (ID, order, product, quantity, prices)

## Setup Instructions

1. Create a MySQL database named `GM`
2. Run the `GM Schema.sql` file to create all tables and relationships
3. Import the CSV files into their respective tables using MySQL's LOAD DATA or import tools

## Analytical Queries

The schema file includes comprehensive analytical queries organized into sections:

- **Customer Insights**: Unique customers, order frequency, purchase values
- **Product Performance**: Category analysis, sales volume, revenue by product
- **Sales & Order Trends**: Order counts, average values, date patterns
- **Supplier Contribution**: Product counts, revenue contribution
- **Employee Performance**: Order handling, sales values
- **Order Details Deep Dive**: Quantity analysis, price variations

## Usage

Use these queries to gain insights into:
- Customer behavior and purchasing patterns
- Product popularity and profitability
- Sales trends over time
- Supplier performance
- Employee productivity
- Order composition analysis

## Requirements

- MySQL 5.7+ or compatible database

- Database management tool (MySQL Workbench, phpMyAdmin, etc.) for importing data and running queries
Database management tool (MySQL Workbench, phpMyAdmin, etc.) for importing data and running queries
