# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The objective is to uncover insights into spending patterns, customer segmentation, subscription behavior, and product performance to support strategic business decision-making.

The project follows an end-to-end analytics workflow using **Python, PostgreSQL, and Power BI**.

---

## 📊 Dataset Summary

- **Total Records:** 3,900 transactions  
- **Total Columns:** 18  
- **Missing Values:** 37 missing values in the `review_rating` column  

### Key Features:
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Shopping Behavior:** Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type  

---

## 🛠️ Tech Stack

- **Python** (Pandas, NumPy) – Data cleaning, preprocessing & feature engineering  
- **PostgreSQL** – Structured business analysis & transactional queries  
- **Power BI** – Interactive dashboard & visualization  
- **GitHub** – Version control & documentation  

---

## 🧹 Data Preparation (Python)

- Loaded dataset using Pandas
- Performed exploratory analysis using `df.info()` and `df.describe()`
- Handled missing values in `review_rating` using median rating per product category
- Standardized column names (snake_case format)
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Dropped redundant column (`promo_code_used`)
- Loaded cleaned dataset into PostgreSQL for SQL-based analysis

---

## 🗄️ Business Analysis (PostgreSQL)

Key business questions answered:

1. Revenue comparison by gender  
2. High-spending discount users  
3. Top 5 products by average rating  
4. Shipping type comparison (Standard vs Express)  
5. Subscribers vs Non-Subscribers revenue & spending  
6. Discount-dependent products  
7. Customer segmentation (New, Returning, Loyal)  
8. Top 3 products per category  
9. Repeat buyers and subscription likelihood  
10. Revenue contribution by age group  

---

## 📈 Key Insights

- Male customers generated higher total revenue compared to female customers.
- Loyal customers form the majority segment.
- Express shipping users have slightly higher average purchase amounts.
- Certain products (e.g., Hats, Sneakers, Coats) show high dependency on discounts.
- Young Adults contributed the highest revenue among age groups.
- Repeat buyers are more likely to subscribe.

---

## 📊 Power BI Dashboard

An interactive dashboard was built to visualize:

- Total Customers (3.9K)
- Average Purchase Amount (~$59.76)
- Average Review Rating (~3.75)
- Revenue by Category
- Revenue by Age Group
- Subscription Distribution
- Sales Trends by Category

The dashboard enables stakeholders to make data-driven marketing and product decisions.

---

## 💡 Business Recommendations

- Boost subscription programs with exclusive benefits.
- Implement loyalty rewards for repeat buyers.
- Optimize discount strategies to protect margins.
- Promote top-rated and best-selling products.
- Target high-revenue age groups through personalized campaigns.
- Leverage express shipping users for premium offers.

---


## 🚀 Project Outcome

This project demonstrates:

- End-to-end data analytics workflow
- Data cleaning & feature engineering
- SQL-based business intelligence
- Customer segmentation & revenue analysis
- Dashboard storytelling for stakeholders

It highlights strong skills in **Data Analysis, SQL, Business Intelligence, and Data-Driven Decision Making**.
