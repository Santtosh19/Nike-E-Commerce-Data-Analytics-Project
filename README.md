# Nike-E-Commerce-Data-Analytics-Project
The project involves designing a relational database, writing SQL queries to manage data, and visualizing the results using Power BI.  The main objectives of this project are to analyze customer purchases, product performance, payment methods, and delivery efficiency for Nike's e-commerce operations.
## Business Problems Addressed
1. Total Orders per Product: What is the distribution of orders among products?
2. Total Sales by Product: Which products generated the highest sales revenue?
3. Top 5 Customers by Spending: Who are the highest-spending customers?
4. Preferred Payment Methods: What are the most common payment methods?
5. Delivery Times: How long does each delivery take, and is there room for improvement?
6. Revenue Trends by Month: How does revenue change over time?
## Files in the Repository
- `TABLES.sql`: SQL script to create tables for the database.
- `DATA INSERT.sql`: Data needed for the database
- `Nike_Ecommerce.svg`: Entity-relationship diagram of the database and tables
- `nike_ecommerce_visz.pbix`: Power BI file containing the visualizations.
- File: https://mega.nz/folder/GVFX1JbA#7YmSueJvj33VQY18ElulAg
## Database Schema
The database design follows an e-commerce model, featuring multiple relationships between customers, products, orders, and payments. The entity-relationship diagram (ERD) is structured as follows:
### Entities:
- Customers: Details of customers including name, contact, and address.
- Categories: Types of products (e.g., shoes, apparel, accessories).
- Products: Nike products along with pricing and category.
- Orders: Customer orders linked to products and payment.
- Product_Order: Relationship table between products and orders (handles multiple products per order).
- Payments: Types of payments (e.g., Visa, PayPal).
- Deliveries: Order delivery information including delivery date.
### ER Diagram:
![Screenshot (935)](https://github.com/user-attachments/assets/93e3631a-367d-4b6e-9b1c-9bb8a578f67a)
### Sample Dashboard:
![Screenshot (936)](https://github.com/user-attachments/assets/62612966-da5a-4ba5-b896-16710a8936fc)
### What Others Can Do:
Anyone who wants to recreate the project can:

1. Download the files.
2. Use the provided SQL script to create the database and tables in their own MySQL instance.
3. Populate the tables using the sample data in the script.
4. Open the Power BI file to see the dashboard or create their own visualizations using the database.

