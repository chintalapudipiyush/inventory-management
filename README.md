# inventory-management

# Inventory Management System

This is a simple Inventory Management System implemented in Python using MySQL database for storage. It allows three types of users: Admin, Customer, and Supplier to interact with the inventory.

## Features

- **Admin**:
  - Can check the existing stock.
  - Can order more stock.
  - Can exit the system.
  
- **Customer**:
  - Can view existing stock.
  - Can add items to the cart and place orders.
  - Can view total amount to be paid and checkout.
  - Can exit the system.
  
- **Supplier**:
  - Can view remaining orders.
  - Can update the stock by supplying ordered items.
  - Can exit the system.
  
## Setup

1. **Database Setup**:
   - Create a MySQL database named `inventory`.
   - Import the provided SQL file `inventory.sql` to set up the necessary tables.

2. **Python Environment**:
   - Make sure you have Python installed on your system.
   - Install the required dependencies using pip:
     ```
     pip install mysql-connector-python prettytable
     ```

3. **Configuration**:
   - Open the Python script `inventory_management.py` and update the database connection details such as `host`, `user`, `passwd`, and `database` according to your MySQL setup.

4. **Running the Script**:
   - Execute the Python script `inventory_management.py`.
   - Choose the appropriate login option (Admin, Customer, or Supplier) and follow the prompts to interact with the system.

## Usage

- **Admin**: 
  - Login with admin credentials and choose options to check stock, order stock, or exit.

- **Customer**:
  - Login with customer credentials and browse the available stock.
  - Enter the PID of items to add them to the cart.
  - Finish adding items by entering 'F'.
  - View the total amount to be paid and checkout.

- **Supplier**:
  - Login with supplier credentials to view remaining orders.
  - Choose to supply ordered items or exit.
