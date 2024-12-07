# La Comanda - API Project

This project, **La Comanda**, was developed for the **Programming 3** subject at **Universidad Tecnológica Nacional (UTN)**.

## Overview

**La Comanda** is an API designed to manage the operations of a restaurant. It implements a variety of use cases for managing users, products, tables, orders, surveys, and generating reports. The system also supports importing and exporting data to and from CSV and PDF formats.

## Features

The API includes the following functionalities:

### User Management
- **Add Users**: Register new employees with their respective roles.
- **List Users**: Display a list of all registered users.

### Product Management
- **Add Products**: Register new food or beverage products.
- **List Products**: Display a list of all registered products.

### Table Management
- **Add Tables**: Register new tables.
- **List Tables**: Display a list of all registered tables.

### Order Management
- **Create Order**: Register a new customer order.
- **List Pending Orders**: View pending orders specific to an employee's role.
- **Update Order Status**: Change order status to "In Preparation" or "Ready to Serve."
- **View Order Delay**: Customers can view the remaining time for their orders.

### Table Status Management
- **Update Table Status**: Change the status of a table (e.g., waiting for an order, eating, paying, or closed).

### Surveys
- **Complete Satisfaction Survey**: Customers can complete a satisfaction survey after finishing their meals.

### Reports and Statistics
- **Employee Statistics**: View employee performance over a specified time.
- **Order Statistics**: View statistics about orders over a specified time.
- **Table Statistics**: View statistics about tables over a specified time.

### Data Import and Export
- **Import Data**: Import employees, products, tables, and orders from a CSV file.
- **Export Data**: Export data to CSV or PDF format, including reports with the company logo.

## Project Structure

- **Database**: The database schema is provided in the file `la_comanda.sql`.
- **Postman Collections**: The Postman collections to interact with the API are included in `LA COMANDA.postman_collection.json`.

## Requirements

- **PHP**: The project is developed using PHP.
- **Database**: A relational database is required to run the project (import `la_comanda.sql`).
- **Postman**: Use the Postman collection to test and interact with the API.

## How to Use

1. Clone the repository to your local machine.
2. Import the `la_comanda.sql` file into your database system to set up the database schema.
3. Use the `LA COMANDA.postman_collection.json` with Postman to interact with the API.
4. Start your PHP server and configure it to point to the project's API files.

## License

This project was created as part of a university assignment and is intended for educational purposes only.

<div style="text-align:center">
  <img src="./UTN_logo.png" alt="UTN Logo" width="450"/>
</div>