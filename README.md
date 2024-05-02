# Dealership-database
This repository contains the SQL scripts to set up and populate a database for managing a dealership's operations. The database includes tables for storing information about customers, employees, vehicles, sales, and more.

## Overview

Tables: The database consists of several tables, including customer, employee, vehicle, sale, and more, each serving a specific purpose in managing dealership operations.
Data: Sample data is provided for each table, showcasing how the database can be populated with realistic information.
Relationships: The tables are connected through foreign key constraints, ensuring data integrity and enabling efficient querying of related information.
Views: Temporary views such as customerview and saleview are included to facilitate specific data presentation needs. Saleview is created to show which employee helped sale a particular vehicle to a certain customer.

## Table Structure

<img width="755" alt="Screenshot 2024-05-02 at 2 06 21 PM" src="https://github.com/KWalker-1/Dealership-database/assets/168217676/5a440328-ac96-4310-9313-6418f88c4530">

Customers: Information about customers, including their names, contact details, and addresses.
Employees: Details about dealership staff, including their roles, contact information, and work addresses.
Vehicles: Data related to vehicles available for sale, such as make, model, color, and price.
Sales: Records of vehicle sales, linking customers, employees, and vehicles involved in each transaction.

## Usage

Database Setup: Execute the provided SQL script to create the dealership database and its tables.
Data Population: Optionally, populate the tables with sample data to test functionality.
Customization: Modify the database structure or add additional tables/views as per your dealership's specific requirements.

## Getting Started

To get started with the Dealership Database:

Clone this repository to your local machine.
Import the SQL script into your preferred database management system.
Execute the script to create the database structure and optionally populate it with sample data.
Start querying the database to manage dealership operations efficiently.
