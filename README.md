# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project focuses on analyzing **customer shopping behavior** for a retail business using **Python, SQL, and Power BI**.  
The goal is to uncover insights related to **customer segments, purchasing patterns, product performance, discounts, subscriptions, and revenue drivers** to support data-driven business decisions.

---

## 🎯 Business Problem
A retail company wants to understand:
- How customers behave across different product categories
- What factors influence purchasing and repeat buying
- The impact of discounts, subscriptions, shipping types, and demographics on revenue

**Key Question:**  
> *How can customer shopping data be leveraged to improve engagement, optimize marketing strategies, and increase revenue?*

---

## 📊 Dataset Summary
- **Total Records:** 3,900 transactions  
- **Total Features:** 18  
- **Data Includes:**
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Item, Category, Amount, Season, Size, Color)
  - Shopping behavior (Discount, Reviews, Purchase Frequency, Shipping Type)
- **Missing Values:** Review ratings (handled during preprocessing)

---

## 🛠️ Tech Stack
- **Python:** Data cleaning, preprocessing, feature engineering
- **SQL (PostgreSQL):** Business queries & analytical insights
- **Power BI:** Interactive dashboard & visual storytelling

---

## 🔄 Project Workflow
1. **Data Cleaning & Preparation (Python)**
   - Handled missing values using category-wise median imputation
   - Standardized column names
   - Created derived features like `age_group` and purchase frequency
   - Loaded cleaned data into PostgreSQL

2. **Data Analysis (SQL)**
   - Revenue analysis by gender and age group
   - High-spending discount users identification
   - Subscriber vs non-subscriber behavior
   - Top products by rating and sales
   - Customer segmentation (New, Returning, Loyal)
   - Discount dependency analysis

3. **Visualization (Power BI)**
   - KPI cards (customers, average spend, ratings)
   - Revenue & sales by category and age group
   - Subscription and shipping analysis
   - Interactive filters for deep exploration

---

## 📈 Key Insights
- **Male customers generated higher total revenue**
- **Loyal customers dominate the customer base**
- **Subscribers contribute significantly to long-term revenue**
- **Certain products are highly discount-dependent**
- **Young adults contribute the highest revenue**
- **Express shipping users show slightly higher average spend**

---

## 💡 Business Recommendations
- Promote **subscription plans** with exclusive benefits
- Strengthen **customer loyalty programs**
- Optimize **discount strategies** to protect margins
- Highlight **top-rated and best-selling products**
- Use **targeted marketing** for high-revenue age groups

---

## 📊 Power BI Dashboard
The Power BI dashboard provides:
- Customer segmentation overview
- Revenue and sales trends
- Subscription and shipping impact analysis
- Interactive filters for dynamic insights
- -
<img width="1320" height="792" alt="image" src="https://github.com/user-attachments/assets/54f3f863-60a0-422e-9275-e32564e0eb11" />

