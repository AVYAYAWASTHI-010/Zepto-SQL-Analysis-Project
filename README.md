# 🛒 Zepto SQL Analysis

## 📌 Project Overview
This project involves analyzing **Zepto's product data** using **PostgreSQL** to generate actionable business insights.  
The database includes information about **products, categories, pricing, discounts, stock levels, and inventory weights**.

The analysis focuses on **data cleaning, exploration, and advanced SQL analytics** to identify:
- Top-performing products
- Categories generating the most revenue
- Inventory and stock management insights
- Pricing and discount patterns

The dataset used for this project was sourced from **[Kaggle] https://www.kaggle.com/datasets/palvinder2006/zepto-inventory-dataset/data?select=zepto_v2.csv**.

---

## 📂 Files in This Repository
| File Name                  | Description |
|----------------------------|-------------|
| `ZeptoDatabaseSchema.png`  | ERD of the database showing table structure |
| `Zepto_v2`                | CSV file containing sample data |
| `Zepto_SQL_Analysis_Queries` | SQL queries for data exploration and analysis |
| `README.md`                | Project documentation |

---

## 🗂️ Database Schema
Below is the schema diagram representing the structure of the Zepto database:

![Zepto Database Schema](https://github.com/AVYAYAWASTHI-010/Zepto-SQL-Analysis-Project/blob/main/ZeptoDatabaseSchema.jpg)

---

## 🧾 Sample Analysis Questions
Here are some of the business questions answered in this project:

1. **Find the top 10 best-value products** based on discount percentage.  
2. **Identify products with high MRP but currently out of stock.**  
3. **Calculate estimated revenue for each category.**  
4. **Find products with MRP > ₹500 and discount < 10%.**  
5. **Top 5 categories with the highest average discount percentage.**  
6. **Determine price per gram for products above 100g.**  
7. **Categorize products into weight groups:** Low, Medium, and Bulk.  
8. **Calculate total inventory weight per category.**  
9. **Products appearing multiple times in the catalog.**  
10. **Products with zero pricing or missing information.**

---

## ⚙️ Tech Stack
- **Database:** PostgreSQL  
- **Language:** SQL  
- **Data Source:** Kaggle  

---
## 🚀 How to Run This Project
Follow these steps to set up and run the analysis:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/AVYAYAWASTHI-010/Zepto-SQL-Analysis.git
cd Zepto-SQL-Analysis

# 2️⃣ Import the database into PostgreSQL
\i zepto.sql

# 3️⃣ Run the analysis queries
\i Zepto_SQL_Analysis_Queries
