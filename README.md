# Olist Brazilian E-Commerce Analysis | Power BI Portfolio Project

## 📌 Project Overview

This project analyzes the Olist Brazilian E-Commerce dataset to understand business performance across sales, customers, products, sellers, delivery, and customer experience.

I used Microsoft Power BI to clean and transform the data, build a relational data model, create DAX measures, and develop an interactive six-page dashboard.

The goal was to turn raw e-commerce data into useful business insights that could support decisions around sales performance, customer experience, operations, and growth.

---

## ❓ Business Questions

The analysis was built around the following questions:

- How much sales and revenue did the business generate?
- Which product categories contribute the most to sales and revenue?
- Which sellers generate the most sales?
- How many orders and customers does the business have?
- How efficient is the delivery process?
- What is the late delivery rate?
- How do customer review scores vary?
- Which Brazilian states have the highest customer and order activity?
- What is the cancellation rate?
- What is the average order value?

---

## 📊 Dataset

**Source:** Olist Brazilian E-Commerce Public Dataset — Kaggle

The dataset contains information from Olist's Brazilian e-commerce operations between 2016 and 2018.

The analysis uses data from:

- Customers
- Geolocation
- Orders
- Order Items
- Payments
- Reviews
- Products
- Sellers
- Product Categories

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Data modeling, DAX, and dashboard development
- **Power Query** — Data cleaning and transformation
- **DAX (Data Analysis Expressions)** — Business measures and KPIs
- **Data Visualization** — Interactive charts, cards, tables, and analytical visuals

---

## 🧹 Data Cleaning & Transformation

Before building the dashboard, I prepared the datasets in Power Query.

Key tasks included:

- Checking for missing values
- Checking for duplicate records
- Cleaning customer city names
- Cleaning review data
- Checking data types and column consistency
- Creating a dedicated Date table
- Establishing relationships between the different tables
- Preparing the data model for analysis

---

## 🧩 Data Modeling

I connected the different datasets to allow the analysis to move between customers, orders, products, sellers, payments, reviews, and dates.

The model allows business performance to be analyzed across different dimensions such as:

- Time
- Customer
- Location
- Product
- Product category
- Seller
- Order
- Payment
- Review

---

## 🧮 DAX Measures

I created a number of DAX measures to support the analysis, including:

- Total Sales
- Total Revenue
- Total Orders
- Total Customers
- Total Products
- Total Sellers
- Total Freight
- Average Order Value
- Average Delivery Days
- Late Delivery Rate
- Cancellation Rate
- Average Review Score
- Orders per Customer

---

# 📈 Key Business Insights

## Sales & Product Performance

The business generated approximately **13.59M in Total Sales** based on the dashboard's Total Sales measure.

The **Beauty & Health** category was one of the strongest-performing categories and made a significant contribution to overall sales performance.

The analysis also highlighted differences in performance across product categories and sellers, making it possible to identify the strongest contributors to sales.

## 🚚 Delivery & Customer Experience

Delivery performance is an important part of the customer experience.

The dashboard shows that periods with higher late-delivery activity can coincide with lower average review scores, suggesting that delivery performance may influence customer satisfaction.

This makes late deliveries an important operational area for further investigation.

## ⭐ Customer Reviews

Five-star reviews make up the largest share of customer ratings in the dataset, showing that many customers reported positive experiences.

However, one-star reviews also represent a significant group. These lower ratings provide an opportunity to investigate the causes of poor customer experiences, including possible delivery or order-related issues.

## 🌍 Geographic Performance

Customer activity is highly concentrated in **São Paulo (SP)**, making it the most prominent customer market in the dataset.

The geographic analysis also shows differences in customer activity, orders, sales, and revenue across Brazilian states.

This provides an opportunity to investigate markets outside the strongest existing regions.

## ⚙️ Operational Performance

The dashboard tracks cancellation and delivery performance over time.

The cancellation rate shows a significant decline between 2016 and 2018, indicating an improvement in order fulfillment during the period covered by the dataset.

However, late deliveries remained a recurring operational issue, with visible spikes in certain months that require further investigation.

---

# 💡 Business Recommendations

Based on the analysis, I would recommend the following actions:

### 1. Improve Delivery Performance

Investigate the causes of late deliveries by looking at delivery times, sellers, locations, and periods with unusually high late-order activity.

Reducing delivery delays could improve the overall customer experience.

### 2. Monitor Seller Performance

Regularly track seller sales and operational performance to identify high-performing sellers and sellers that may require additional support.

### 3. Protect High-Performing Categories

Continue monitoring strong product categories such as Beauty & Health while identifying opportunities to improve the performance of weaker categories.

### 4. Explore Geographic Growth

Since customer activity is concentrated in certain states, investigate other regions with potential for customer growth.

Targeted marketing and improved logistics could help expand the customer base.

### 5. Monitor Customer Experience

Track review scores alongside delivery and order performance to identify recurring problems and improve customer satisfaction.

---

# 📂 Dashboard Structure

The Power BI report contains six pages:

### 1. Executive Overview

High-level KPIs covering sales, revenue, orders, customers, products, and overall business performance.

### 2. Customer & Order Analysis

Analysis of customer activity, order volume, and purchasing patterns.

### 3. Delivery & Customer Experience

Analysis of delivery performance, delivery times, late deliveries, cancellations, and customer reviews.

### 4. Product & Seller Performance

Analysis of product categories, sales, revenue, and seller performance.

### 5. Geographic Customer Analysis

Analysis of customers, orders, sales, and revenue across Brazilian states.

### 6. Executive Summary

A consolidated view of the most important business performance indicators.

---

# 📷 Dashboard Preview

### Executive Overview

_Add screenshot of Page 1 here._

### Delivery & Customer Experience

_Add screenshot of Page 3 here._

### Product & Seller Performance

_Add screenshot of Page 4 here._

### Executive Summary

_Add screenshot of Page 6 here._

---

# ⚠️ Limitations

- The dataset contains historical transactions from 2016–2018 and therefore does not represent the current Brazilian e-commerce market.
- Sellers are mainly represented by seller IDs, which limits the amount of descriptive information available about individual sellers.
- The analysis is limited to the information available in the original Olist dataset.
- Observed relationships between delivery performance and customer reviews should not be interpreted as proof of causation without further statistical analysis.

---

# 📚 What I Learned

This project gave me practical experience taking a real-world dataset from raw data to an interactive business intelligence dashboard.

Through the project, I improved my ability to:

- Clean and prepare data
- Build relationships between tables
- Create DAX measures
- Design Power BI dashboards
- Select appropriate visualizations
- Analyze business performance
- Identify trends and patterns
- Communicate data-driven findings
- Turn analysis into practical recommendations

---

# 🎯 Conclusion

This project demonstrates my ability to work through a complete data analysis workflow, from data preparation and modeling to DAX, visualization, and business interpretation.

Rather than focusing only on creating visuals, I used the dashboard to answer specific business questions and translate the results into actionable recommendations.

The project strengthened my practical Power BI and analytical skills and forms part of my data analyst portfolio.

---

## 🔗 Interactive Dashboard

_Add a link here if the Power BI report is published online._
