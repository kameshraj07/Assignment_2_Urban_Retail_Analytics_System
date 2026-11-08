# Assignment 2 – Urban Retail Analytics System

## Project Overview

The **Urban Retail Analytics System** is a Python-based project designed to automate and simplify retail business operations.

The project demonstrates how Python can be used to manage sales calculations, customer orders, inventory, transaction auditing, and store branch information.

It applies fundamental and intermediate Python programming concepts to solve real-world retail business problems.

## Objectives

- Calculate sales tax and final product prices.
- Categorize customer orders based on quantity.
- Audit daily sales transactions.
- Calculate customer discounts and loyalty points.
- Manage product prices and inventory information.
- Store and process retail business data.
- Handle errors and exceptions.
- Create and use custom Python modules.
- Apply Object-Oriented Programming (OOP) concepts.

## Technologies Used

- **Programming Language:** Python 3
- **IDE:** Visual Studio Code
- **File Format:** Python (`.py`) and Markdown (`.md`)

## Project Tasks

### 1. Sales Tax Calculator

- Accept the base price from the user.
- Calculate 10% sales tax.
- Display the final price including tax.

### 2. Order Quantity Categorization

Classify customer orders based on quantity:

| Quantity | Order Category |
|---|---|
| 10 or more | Bulk Wholesale Order |
| 3 to 9 | Standard Customer Order |
| Less than 3 | Single Item Purchase |

### 3. Daily Sales Auditor

- Use a list of sales transactions.
- Skip invalid transactions using `continue`.
- Identify high-value orders.
- Stop the audit using `break` when a transaction exceeds ₹250.

### 4. Customer Discount Calculator

- Calculate a 15% discount for VIP customers.
- Calculate a 5% discount for regular customers.
- Use functions to calculate the final bill amount.

### 5. Customer Loyalty Points

Use a lambda function to calculate loyalty points.

- One loyalty point is awarded for every ₹10 spent.

### 6. Recursive Tier Bonus

Use recursion to calculate additional customer tier bonuses.

### 7. Python Data Structures

The project uses the following Python data structures:

- **Tuple:** Store headquarters coordinates.
- **Set:** Remove duplicate customer email addresses.
- **Dictionary:** Store and update product stock quantities.
- **List Comprehension:** Calculate discounted product prices.

### 8. File Handling

Use Python file handling to maintain retail audit records.

- Open files in append mode.
- Add daily audit messages.
- Save records in `audit_log.txt`.

### 9. Exception Handling

Use `try`, `except`, `else`, and `finally` to handle invalid store ID inputs and prevent program errors.

### 10. Python Modules

Use built-in modules:

- `random` – Generate order tracking numbers.
- `datetime` – Retrieve the current date.

Create a custom module named `inventory_utils.py` containing the `check_stock(quantity)` function.

The main script imports and calls this function to check inventory availability.

### 11. Object-Oriented Programming

Create a parent class named `StoreBranch`.

**StoreBranch**

- Class variable: `company_name = "Urban Retail"`
- Instance variables: `branch_id` and `_daily_revenue`
- Method: `get_revenue()` to access branch revenue.

Create a child class named `FlagshipStore`.

**FlagshipStore**

- Inherits from `StoreBranch`.
- Includes `vip_lounge_access`.
- Uses `super().__init__()` to initialize parent class variables.
- Overrides `get_revenue()` to add ₹500 to the original revenue.

**Example:**

- Branch ID: 101
- Initial Revenue: ₹2,000
- VIP Lounge Access: True
- Additional VIP Revenue: ₹500
- Final Revenue: ₹2,500

## Project Folder Structure

```text
Assignment_2_Urban_Retail_Analytics_System/
│
├── inventory_utils.py
├── main.py
├── audit_log.txt
└── README.md
```

## Conclusion

The Urban Retail Analytics System demonstrates how Python programming concepts can be applied to retail business operations. This assignment provides practical experience in writing reusable code, organizing Python modules, handling business data, and developing object-oriented applications.
