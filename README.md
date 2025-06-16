# Relational Database: Customer, Product, Orders

This project demonstrates a simple relational database schema using SQL, including table creation, relationships, and data insertion using DDL and DML commands.

## 🗃️ Database Schema

- **Customer** (`Customer_id`, `customer_Name`, `customer_Tel`)
- **Product** (`Product_id`, `product_name`, `category`, `Price`)
- **Orders** (`Customer_id`, `Product_id`, `OrderDate`, `quantity`, `total_amount`)

### Relationships

- `Customer_id` in **Orders** references `Customer_id` in **Customer**
- `Product_id` in **Orders** references `Product_id` in **Product**
- **Orders** uses a composite primary key: (`Customer_id`, `Product_id`)

## ⚙️ SQL Features Used

- **DDL**: `CREATE TABLE`, `ALTER TABLE`
- **DML**: `INSERT INTO`
- **Constraints**: `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `CHECK`

## 📥 Sample Data Inserted

- Customers: Ali, Asma
- Products: Samsung Galaxy S20, PC
- Orders: 2 sample records with quantities and total amounts

## 📄 SQL File Contents

- Table creation commands
- Insert statements
- Constraint definitions

## 💡 Usage

Run the SQL scripts using your preferred database client (Oracle, MySQL, or PostgreSQL) to create the tables and insert sample data.

## 📁 File Structure

📦project-root/
┣ 📄 check.sql
┗ 📄 README.md


## 🧑‍💻 Author

Karim Chebbi  
