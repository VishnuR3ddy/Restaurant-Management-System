# Restaurant Management System

## Overview
This project is a comprehensive database management system for a restaurant, aimed at improving time and inventory management, food quality, and customer service. The system organizes restaurant operations into departments, tracks employees, manages inventory, and processes orders, all while offering customers personalized services, including feedback and order tracking.

## General Problem Description
The restaurant industry faces challenges such as time and inventory management, reducing food wastage, and ensuring high-quality service. This system leverages database management to streamline operations, from managing departments and employee schedules to tracking customer orders and inventory items.

## Key Components

### Employee
- Each employee has a unique ID and is assigned to one department.
- Employees have a daily schedule and tasks, with each having a supervisor.
- **Details:** ID, Name, DOB, Gender, Email, Phone#, Address, Salary.

### Customer
- Customers can sign up and provide personal details to receive promotions.
- **Details:** ID, Name, Age, Gender, Email, Phone#, Address.

### Department
- Each department has a unique ID and a supervisor who manages the employees.
- **Details:** Dept_ID, Dept_Name.

### Inventory
- Tracks food items, utensils, and appliances with details like quantity, expiry, and price.
- **Details:** Item ID, Name, Mfg. Date, Expiry Date, Qty Purchased, Price, Qty Left.

### Supplier
- Suppliers provide necessary items for inventory.
- **Details:** Supplier ID, Name.

### Order
- Customers place orders based on the menu, tracked in the system.
- **Details:** Order ID, Type, Price, Placed Time, Served Time, Category.

### Feedback
- Customers provide feedback, which is stored and analyzed.
- **Details:** Order ID, Suggestions, Complaints, Rating (out of 10).

### Daily Schedule
- Employees are assigned schedules and tasks.
- **Details:** Start Time, End Time, Task.

## Business Goals
- Increase daily sales by 10% next quarter.
- Improve Dine-in service by 9% over To-Go service.
- Reduce serving time to under 10 minutes.
- Minimize food wastage to 10% per day.
- Track customer preferences, aiming for more 18-25-year-olds.
- Optimize inventory by analyzing peak order days.

## Functional Requirements
- Manage orders and inventory in real-time.
- Generate customer receipts with order and payment details.
- Offer both Dine-in and To-Go options.
- Analyze sales trends and customer preferences.

## Installation
1. Clone the repository.
2. Set up the database schema provided in `/schema.sql`.
3. Configure the database connection in `config.py`.
4. Run the application using:
    ```bash
    python app.py
    ```

## Restrictions
This project is for academic purposes only and **cannot be used** or redistributed by others without permission.

## License
This project is licensed under the MIT License.

## Contact
- **Contributors:** Vishnu Reddy
- **Email:** vishnureddy912171@gmail.com
