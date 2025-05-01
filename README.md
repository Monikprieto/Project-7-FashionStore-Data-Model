# Project-7-FashionStore-Data-Model
FASHIONSTORE DATA MODEL - SQL ARCHITECTURE

Introduction
This project designs and implements a comprehensive relational database for an **online clothing retail company**, supporting essential business processes like inventory management, customer tracking, sales processing, supplier management, and order fulfillment.

Project Overview
The goal of this project is to create a normalized and scalable SQL schema that reflects real-world retail operations. The database serves as a foundation for integrating analytics tools like Power BI or Tableau to support data-driven decision-making.

Database Structure

Core Modules:
- **Products and Inventory**
  - Product catalog with size, color, and stock tracking
  - Product categories and last update time

Sales and Orders**
  - Customer orders, itemized order details, and payment records

Customers**
  - Customer profiles and address management

Suppliers and Purchases**
  - Supplier records, purchase orders, and received inventory

Extensions:
- Admin users and roles
- Product images and variants
- Customer reviews and wishlists
- Return and refund tracking

 Tools Used

- **dbdiagram.io** – ERD visualization and schema design  
- **PostgreSQL** – SQL code implementation  
- **Power BI / Tableau (optional)** – Data visualization and BI dashboards  

Development

eRD
You can view or edit the database schema visually on [dbdiagram.io](https://dbdiagram.io) by importing the ERD definition.

SQL Schema
All tables were created using PostgreSQL syntax. Core tables include:

- `product_categories`
- `products`
- `inventory`
- `customers`
- `customer_addresses`
- `orders`
- `order_items`
- `payments`
- `suppliers`
- `purchases`
- `purchase_items`

Each table uses appropriate foreign key relationships to maintain data integrity.

Results and Conclusions

This project successfully implements a robust SQL data model for a digital retail environment. The structure:

- Covers end-to-end retail processes (sales, supply, inventory, customer management)
- It is designed for future scalability and integration
- Enables data warehousing and business intelligence use cases

> Future work could include integration with Python-based ETL pipelines, machine learning for sales forecasting, or customer segmentation analytics.

Project Structure
├── README.md
├── Code_create_tables_sql_sample.txt # SQL 
├──Relation_tables_foreign_keys.csv (export SQL)
    └── ERD.pgerd              # ERD model file (.png export)

Author
Monica Prieto — Data Engineer

