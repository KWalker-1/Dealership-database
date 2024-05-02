# Dealership-database
This repository contains the SQL scripts to set up and populate a database for managing a dealership's operations. The database includes tables for storing information about customers, employees, vehicles, sales, and more.

## Overview

1. Tables: The database consists of several tables, including customer, employee, vehicle, sale, and more, each serving a specific purpose in managing dealership operations.
2. Data: Sample data is provided for each table, showcasing how the database can be populated with realistic information.
3. Relationships: The tables are connected through foreign key constraints, ensuring data integrity and enabling efficient querying of related information.
4. Views: Temporary views such as customerview and saleview are included to facilitate specific data presentation needs. Saleview is created to show which employee helped sale a particular vehicle to a certain customer.

## Table Structure

<img width="755" alt="Screenshot 2024-05-02 at 2 06 21 PM" src="https://github.com/KWalker-1/Dealership-database/assets/168217676/5a440328-ac96-4310-9313-6418f88c4530">

1. Customers: Information about customers, including their names, contact details, and addresses.
2. Employees: Details about dealership staff, including their roles, contact information, and work addresses.
3. Vehicles: Data related to vehicles available for sale, such as make, model, color, and price.
4. Sales: Records of vehicle sales, linking customers, employees, and vehicles involved in each transaction.

## Getting Started

To get started with the Dealership Database:

1. Download the provided SQL dump file.
2. Create a database called "dealership". (If you wish to call it something else you may modify the dump file and switch out "dealership" on line 2 for your desired name.)
3. "USE dealership;"
4. "SOURCE /pathway to location of file/Dealership.sql;"
5. Finally "SHOW tables;" to make sure it uploaded successfully.


## Usage

1. Database Setup: Execute the provided SQL script to create the dealership database and its tables.
2. Data Population: Optionally, populate the tables with sample data to test functionality.
3. Customization: Modify the database structure or add additional tables/views as per your dealership's specific requirements.

