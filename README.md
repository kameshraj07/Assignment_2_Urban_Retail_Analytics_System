# 🏬 Urban Retail Analytics System

## 📌 Project Overview

The **Urban Retail Analytics System** is a Python-based project designed to automate and simplify retail business operations.

This project demonstrates how Python programming can be applied to real-world retail scenarios, including sales calculations, customer order management, inventory tracking, transaction auditing, customer discounts, and store branch management.

It incorporates fundamental and intermediate Python concepts such as functions, loops, lambda expressions, recursion, data structures, file handling, exception handling, modules, and Object-Oriented Programming (OOP).

## 🎯 Project Objectives

- Calculate sales tax and final product prices.
- Categorize customer orders based on quantity.
- Audit daily sales transactions.
- Calculate customer discounts and loyalty points.
- Implement recursive customer tier bonuses.
- Manage product prices and inventory information.
- Store and process retail business data.
- Handle runtime errors using exception handling.
- Create and import custom Python modules.
- Apply Object-Oriented Programming concepts.

## 🛠️ Technologies Used

| Technology | Description |
|---|---|
| Python 3 | Programming language |
| Visual Studio Code | Development environment |
| Markdown | Project documentation |
| Git & GitHub | Version control and project hosting |

## 📂 Project Folder Structure

```text
Assignment_2_Urban_Retail_Analytics_System/
│
├── inventory_utils.py    # Custom inventory module
├── main.py               # Main Python application
├── audit_log.txt         # Retail audit records
└── README.md             # Project documentation
```

## 🚀 Project Features

### 1. Sales Tax Calculator
- Accepts the base product price from the user.
- Calculates 10% sales tax.
- Displays the final price, including tax.

### 2. Order Quantity Categorization

Categorizes customer orders based on purchase quantity.

| Quantity | Order Category |
|---|---|
| 10 or more | Bulk Wholesale Order |
| 3 to 9 | Standard Customer Order |
| Less than 3 | Single Item Purchase |

### 3. Daily Sales Auditor
- Uses a list to store sales transactions.
- Skips invalid transactions using `continue`.
- Identifies high-value orders.
- Stops auditing when a transaction exceeds ₹250 using `break`.

### 4. Customer Discount Calculator
- VIP customers receive a 15% discount.
- Regular customers receive a 5% discount.
- Uses functions to calculate the final bill amount.

### 5. Customer Loyalty Points
- Uses a lambda function to calculate loyalty points.
- Awards one loyalty point for every ₹10 spent.

### 6. Recursive Tier Bonus
- Implements recursion to calculate additional customer tier bonuses.
- Demonstrates recursive function execution.

### 7. Python Data Structures

Uses different Python data structures to manage retail information.

| Data Structure | Application |
|---|---|
| Tuple | Stores headquarters coordinates |
| Set | Removes duplicate customer email addresses |
| Dictionary | Stores and updates product stock quantities |
| List Comprehension | Calculates discounted product prices |

### 8. File Handling
- Uses append mode (`a`) to open files.
- Records daily retail audit messages.
- Stores transaction information in `audit_log.txt`.

### 9. Exception Handling
- Uses `try`, `except`, `else`, and `finally`.
- Handles invalid store ID inputs.
- Prevents unexpected program termination due to input errors.

### 10. Python Modules

**Built-in Modules:**

- `random` – Generates unique-style order tracking numbers.
- `datetime` – Retrieves the current date.

**Custom Module:**

- `inventory_utils.py` – Contains the `check_stock(quantity)` function to check inventory availability.

### 11. Object-Oriented Programming (OOP)

Implements inheritance, encapsulation, and method overriding.

**Parent Class: StoreBranch**

- Class variable: `company_name = "Urban Retail"`
- Instance variables: `branch_id` and `_daily_revenue`
- Method: `get_revenue()` accesses the private-style revenue attribute.

**Child Class: FlagshipStore**

- Inherits from `StoreBranch`.
- Includes `vip_lounge_access`.
- Uses `super().__init__()` to initialize parent class attributes.
- Overrides `get_revenue()` to add ₹500 to the original revenue.

**Example Output:**

```text
Branch ID: 101
Initial Revenue: ₹2000
VIP Lounge Access: True
Additional VIP Revenue: ₹500
Final Revenue: ₹2500
```

## 💻 Installation and Setup

### Step 1: Install Python

Download and install Python 3 from:

https://www.python.org/downloads/

Verify the installation:

```bash
python --version
```

### Step 2: Clone the Repository

```bash
git clone https://github.com/your-username/Assignment_2_Urban_Retail_Analytics_System.git
```

### Step 3: Navigate to the Project Directory

```bash
cd Assignment_2_Urban_Retail_Analytics_System
```

### Step 4: Run the Python Application

```bash
python main.py
```

**Note:** Ensure that `main.py` and `inventory_utils.py` are present in the same project directory.

## 📊 Expected Learning Outcomes

By completing this project, I gained practical experience in:

- Python programming fundamentals.
- Conditional statements and looping techniques.
- Functions and lambda expressions.
- Recursive programming.
- Python lists, tuples, sets, and dictionaries.
- File handling and exception management.
- Built-in and custom Python modules.
- Object-Oriented Programming.
- Real-world problem-solving using Python.

## 🔮 Future Enhancements

- Integrate a MySQL database for retail data storage.
- Develop a graphical user interface (GUI).
- Generate automated sales reports.
- Implement customer purchase history.
- Add inventory alerts for low-stock products.
- Create interactive sales analytics dashboards.

## 👨‍💻 Author

**Kamesh Raj**

Aspiring Data Scientist | Python Programmer

## 📜 License

This project is created for educational and learning purposes.

---

⭐ If you find this project useful, feel free to explore and contribute!
