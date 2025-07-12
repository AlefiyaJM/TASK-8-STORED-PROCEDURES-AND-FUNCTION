# Task 8: Stored Procedures and Functions  

## 📌 Overview

This project demonstrates the use of **MySQL stored procedures** and **functions**, utilizing **parameters** and **conditional logic**. It consists of examples that cover creating and testing stored programs using `CREATE PROCEDURE` and `CREATE FUNCTION`.

---

## 🔧 Implemented Concepts

### 1. `CREATE FUNCTION`  
- **Function Name:** `CalculateDiscount`  
- **Purpose:** Calculates the discounted price based on input price and discount percentage.

### 2. `CREATE PROCEDURE`  
- **Procedure Name:** `GetOrdersByUser`  
- **Purpose:** Retrieves orders placed by a specific user using their user ID.

### 3. Parameters and Conditional Logic

#### ✅ Procedure: `CheckOrderValue`  
- **Purpose:** Checks if a particular order is of high or regular value.

#### ✅ Function: `PaymentStatus`  
- **Purpose:** Returns the payment tier status (`Premium`, `Standard`, `Basic`) based on the amount.

#### ✅ Procedure: `GetTotalSpent`  
- **Purpose:** Calculates the total amount spent by a particular user.

---

## ✅ Execution Status

All stored procedures and functions were:
- Successfully created.
- Executed and tested using valid input parameters.
- Produced correct and expected output based on logic and dataset.

---

## 📂 Database Tables Used

- **User**: Stores user details like `user_id` and `u_name`.
- **Orders**: Stores order details like `order_no`, `order_date`, `order_amount`, and `user_id`.

---

## 💡 Notes

- Tested using MySQL with standard delimiters.
- Includes error handling via conditional logic inside stored procedures.
- Demonstrates a clear understanding of control flow with `IF`, `ELSEIF`, and `ELSE`.

---

## 📌 Skills Demonstrated

- SQL Stored Procedures
- SQL Functions
- Use of Parameters
- Conditional Logic (`IF`, `ELSEIF`, `ELSE`)
- Data Aggregation (`SUM`, `GROUP BY`)
- Basic SQL Joins

---

