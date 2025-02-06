# DBA Project Journey: Sales Order Management System

Welcome to the **Sales Order Management System** project, a key component of the DBA Project Journey. This application is designed to provide hands-on experience in database administration by managing sales orders through an interactive interface. The system utilizes PostgreSQL for robust data management and Gradio for a user-friendly web interface.

## Project Overview

This project is part of the DBA Project Journey, aiming to enhance your skills in database design, management, and application development. By working on this Sales Order Management System, you will gain practical experience in:

- Designing and managing relational databases
- Implementing CRUD operations
- Developing interactive web interfaces
- Integrating Python applications with PostgreSQL

## Features

- **Order Management:** Create, update, and delete sales orders.
- **Customer Management:** Manage customer information seamlessly.
- **Product Catalog:** Maintain a list of products with details like price and stock.
- **Real-Time Interaction:** Utilize Gradio to interact with the system in real-time.

## Tech Stack

- **Backend:** Python
- **Database:** PostgreSQL
- **Web Interface:** Gradio

## Installation Guide

Follow these steps to set up the project locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/DBA_PROJECTJOURNEY.git
   cd DBA_PROJECTJOURNEY/SalesOrderManagementSystem
   ```

2. **Set Up a Virtual Environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure PostgreSQL Database:**

   - Ensure PostgreSQL is installed and running on your machine.
   - Create a new database:

     ```sql
     CREATE DATABASE salesDB;
     ```

   - Update the `config.py` file with your database credentials:

     ```python
     DATABASE_URI = 'postgresql://username:password@localhost:5432/salesDB'
     ```

5. **Initialize the Database:**

   ```bash
   python init_db.py
   ```

6. **Run the Application:**

   ```bash
   python app.py
   ```

   Access the application at `http://127.0.0.1:7860/`.

## Usage Guide

Once the application is running:

- **Add a New Customer:**
  - Navigate to the "Customers" section.
  - Fill in the customer details and submit.

- **Add a New Product:**
  - Go to the "Products" section.
  - Enter product information, including price and stock quantity.

- **Create a New Order:**
  - In the "Orders" section, select a customer and add products to the order.
  - Specify quantities and confirm the order.

- **View Orders:**
  - Access the "Order History" to view all orders.
  - Use filters to search for specific orders.

## Resources

you can use the following resources for more guidance

https://www.gradio.app/guides/quickstart

