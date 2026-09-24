# 📊 Sales Analytics & Performance Dashboard

## 📌 Project Overview

This project analyzes sales, profit, quantity, customer, product, category, and payment-mode data to generate meaningful business insights.

The project combines two related datasets, **Details** and **Orders**, using the common **Order ID** field.

The analysis focuses on sales performance, profitability, customer contribution, product sub-category performance, payment-mode distribution, and monthly and quarterly trends.

The final output is an interactive **Power BI Sales Dashboard** containing KPI, product, customer, payment-mode, category, and time-based analysis.

---

## 🎯 Business Objective

The main objective of this project is to analyze sales performance and identify the major factors contributing to revenue and profitability.

The analysis focuses on:

- Overall sales performance
- Total sales amount
- Total profit
- Total quantity sold
- Product category performance
- Sub-category profitability
- Customer-level sales performance
- Payment-mode analysis
- Monthly profit trends
- Quarterly performance
- Identification of high-performing and low-performing segments

---

## 🛠️ Tech Stack

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Cleaning
- Data Transformation
- Data Visualization

---

## 📂 Dataset Structure

The original dataset contains two related sheets:

| Sheet   | Purpose |
| ------- | ------- |
| Details | Contains order-level sales, profit, quantity, category, sub-category, and payment-mode information |
| Orders  | Contains order date, customer, state, and city information |

### Details Sheet

The **Details** sheet contains transaction-level sales information.

| Column | Description |
| ------ | ----------- |
| Order ID | Unique identifier for each order |
| Amount | Sales/order amount |
| Profit | Profit generated from the order |
| Quantity | Number of products purchased |
| Category | Product category |
| Sub-Category | Product sub-category |
| PaymentMode | Payment method used for the order |

Example:

| Order ID | Amount | Profit | Quantity | Category | Sub-Category | PaymentMode |
| -------- | -----: | -----: | -------: | -------- | ------------ | ----------- |
| B-25681 | 1096 | 658 | 7 | Electronics | Electronic Games | COD |
| B-26055 | 5729 | 64 | 14 | Furniture | Chairs | EMI |
| B-25955 | 2927 | 146 | 8 | Furniture | Bookcases | EMI |
| B-26093 | 2847 | 712 | 8 | Electronics | Printers | Credit Card |
| B-25602 | 2617 | 1151 | 4 | Electronics | Phones | Credit Card |

### Orders Sheet

The **Orders** sheet contains customer and geographical information along with order dates.

| Column | Description |
| ------ | ----------- |
| Order ID | Unique identifier used to connect with Details |
| Order Date | Date on which the order was placed |
| CustomerName | Name of the customer |
| State | Customer/order state |
| City | Customer/order city |

Example:

| Order ID | Order Date | CustomerName | State | City |
| -------- | ---------- | ------------ | ----- | ---- |
| B-26055 | 10/3/2018 | Harivansh | Uttar Pradesh | Mathura |
| B-25993 | 3/2/2018 | Madhav | Delhi | Delhi |
| B-25973 | 24-01-2018 | Madan Mohan | Uttar Pradesh | Mathura |
| B-25923 | 27-12-2018 | Gopal | Maharashtra | Mumbai |
| B-25757 | 21-08-2018 | Vishakha | Madhya Pradesh | Indore |

---

## 🔗 Data Relationship

The **Details** and **Orders** sheets are connected using the common:
Order ID
