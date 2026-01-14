<div align="center">
  <img src="https://github.com/sks111/Walmart-Sales-Analysis/blob/main/Walmart_logo_(2008).svg.png" width="350" alt="Walmart Logo"/>
</div>
---

# 🛒 Walmart Sales Analysis  
### End-to-End Data Analytics Project (Python + MySQL)

![Python](https://img.shields.io/badge/Python-EDA-3776AB)
![MySQL](https://img.shields.io/badge/MySQL-Business%20Analysis-4479A1)
![Status](https://img.shields.io/badge/Project-Complete-success)

---

## 📌Summary

This project presents a **comprehensive Walmart Sales Analysis** designed to demonstrate a **structured, real-world data analytics workflow**.  
The analysis follows a two-phase approach:

1. **Exploratory Data Analysis (EDA) using Python** to understand, clean, and validate the data  
2. **Business-driven analysis using MySQL** to answer key retail and operational questions  

The objective is to convert raw transactional data into **reliable, business-ready insights** that can support **sales optimization, operational efficiency, and strategic decision-making**.

---

## 🎯 Business Objectives

The project aims to address the following business goals:

- Evaluate **sales performance** across branches and cities  
- Identify **high-performing and underperforming product categories**  
- Understand **customer purchasing patterns**  
- Analyze **time-based sales behavior** (date and time trends)  
- Examine the relationship between **profit margin and customer ratings**  
- Support data-driven retail decision-making  

---

## 🧠 Dataset Overview

The cleaned dataset (`walmart_cleaned.csv`) represents Walmart transactional sales data.

### Dataset Attributes

| Column | Description |
|------|-------------|
| `invoice_id` | Unique identifier for each transaction |
| `Branch` | Walmart branch code |
| `City` | City where the transaction occurred |
| `category` | Product category |
| `unit_price` | Price per unit of product |
| `quantity` | Number of units sold |
| `date` | Transaction date |
| `time` | Transaction time |
| `payment_method` | Mode of payment |
| `rating` | Customer satisfaction rating |
| `profit_margin` | Profit margin for the transaction |

---

## 🛠️ Tools & Technologies

| Area | Tool |
|---|---|
| Programming Language | Python |
| Data Understanding & Cleaning | Pandas, NumPy |
| Database | MySQL |
| Query Language | SQL |
| Notebook Environment | Jupyter |

---

## 🔍 Phase 1: Exploratory Data Analysis (Python)

The first phase of the project focuses on **understanding and preparing the data** using Python (`walmart.ipynb`).

### EDA Activities Performed

- Validated dataset structure, size, and schema  
- Identified and handled missing or inconsistent values  
- Converted date and time fields into appropriate formats  
- Verified numerical ranges for unit price, quantity, and profit margin  
- Analyzed distributions to detect anomalies and extreme values  
- Performed category-level and branch-level exploratory checks  
- Ensured data consistency before loading into MySQL  

📌 **Key Outcome:**  
The EDA phase ensured that the dataset was **accurate, consistent, and analytically reliable**, forming a strong foundation for SQL-based business analysis.

---

## 🧮 Phase 2: Business Analysis Using MySQL

Once the data was cleaned and validated, it was loaded into **MySQL** for structured business analysis.  
All SQL queries are documented in:

📁 `walmart_sales_queries.sql`

### Business Questions Addressed

- What is the **total sales volume and profit margin** by branch and city?
- Which **product categories** contribute the most to revenue?
- How does **sales performance vary by time (date and hour)**?
- Which **payment methods** are most frequently used and most profitable?
- Is there a relationship between **customer ratings and profit margins**?
- What are the **average transaction values** across branches?

SQL queries use:
- Aggregations (`SUM`, `AVG`)
- Grouping and filtering
- Ranking and sorting
- Date and time-based analysis

---

## 📈 Key Findings & Insights

- Sales and profitability vary significantly across branches and cities  
- A limited number of product categories account for a large share of total revenue  
- Certain time periods consistently show higher sales activity  
- Payment method preferences influence transaction values  
- Higher customer ratings generally align with stronger profit margins  

---

