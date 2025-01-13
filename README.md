# Electricity Billing System

The Electricity Billing System is a user-friendly desktop application designed to simplify and automate the management of electricity billing. It is built using Java with a Swing-based GUI for the front end and MySQL for database management.

# Features

**Customer Management:**

Add, edit, and delete customer details.

View customer information.

**Billing Management:**

Generate electricity bills based on consumption.

Maintain a record of past bills.

**Admin Features:**

Manage customer and billing records.

Access detailed reports.

# Technologies Used

**Frontend:** Java Swing for the graphical user interface.

**Backend:** Java for business logic implementation.

**Database:** MySQL for storing customer, billing, and payment information.

# Prerequisites

To run the project, ensure you have the following installed:

Java Development Kit (JDK) (Version 8 or later)

**MySQL Server**

**Eclipse IDE(optional but recommended for development)**

# Setup and Installation

**Clone the repository:**

git clone https://github.com/Omkar-Abhang/Electricity_Billing_System.git

Import the project into your IDE (e.g., eclipse ide).

**Set up the MySQL database:**

Create a new database in MySQL.

Import the provided SQL script (database_script.sql) to set up the required tables.

**Update the database connection in the Java code:**

Navigate to the database connection file.

Update the username, password, and database name as per your MySQL setup.

Build and run the project from your IDE.

# How to Use

Launch the application: Run the main class from your IDE.

Log in: Enter admin credentials to access the system (default credentials, if any, can be found in the code or documentation).

Manage Customers: Add or update customer details.

Generate Bills: Input customer consumption data and generate bills.

Track Payments: Record payments and review outstanding balances.

# Project Structure

src/: Contains all Java source files.

database_script.sql: SQL script for setting up the database.

lib/: Contains external libraries (if any).

# Future Enhancements

Implement email notifications for bill generation and payment reminders.

Add support for multiple user roles (e.g., Admin, Clerk).

Integrate online payment gateway.

Enhance the UI/UX for better usability.

# License

This project is licensed under the MIT License. You are free to use, modify, and distribute it.

Acknowledgments

Special thanks to Omkar Abhang for creating this project.

Java Swing Documentation for GUI development guidance.

MySQL Documentation for database management.
