# Book Store Management System

A desktop application for managing a book store. It covers books, inventory, customers, employees and orders, and generates printable bills and sales reports. Built with JavaFX and MySQL.

## Features
- Login and registration with hashed passwords, plus change password
- Dashboard with sales overview and monthly charts
- Book management (add, update, delete, search)
- Inventory and stock management
- Customer and employee management
- Billing with printable invoices (JasperReports)
- Order history and order details
- Monthly and yearly sales reports
- Profile and settings pages

## Tech Stack
- Java, JavaFX (FXML + CSS)
- MySQL
- JasperReports
- Maven

## Getting Started
1. Create the database by importing `db.sql` into MySQL.
2. Update the connection details in `src/main/java/fct/cs/dbUtil/DatabaseHandler.java`.
3. Build and run:
   ```bash
   mvn clean javafx:run
   ```

## Reports
The `.jrxml` report designs are in `jasper_project_files/` (edit them with Jaspersoft Studio). The compiled `.jasper` files used by the app are in `src/main/resources/fct/cs/jasper/`.
