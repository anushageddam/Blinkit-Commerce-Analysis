# 🛒 Blinkit Commerce Analysis | End-to-End Data Analytics Project

---

# 📌 Project Overview

This project demonstrates an **end-to-end Business Intelligence solution** for Blinkit, one of India's leading quick-commerce platforms.

The project begins with raw operational datasets and follows the complete analytics lifecycle:

* Data Cleaning using **Python**
* Business Analysis using **SQL (SQLite)**
* Interactive Dashboard Development using **Power BI**
* Business Insights & Recommendations

The objective was to transform raw business data into meaningful insights that help stakeholders monitor sales performance, customer behavior, delivery efficiency, inventory health, and marketing effectiveness.

---

# 🎯 Business Problem

Blinkit handles thousands of customer orders every day across multiple product categories and delivery locations.

Business stakeholders need a centralized analytics solution to answer questions such as:

* Which product categories generate the highest revenue?
* Which products contribute the most to profit?
* How efficient are deliveries?
* What are the major causes of delayed deliveries?
* How satisfied are customers?
* Which marketing channels provide the highest ROI?
* Is inventory managed efficiently?

This project addresses these questions through interactive dashboards and data-driven insights.

---

# 📂 Dataset Overview

The project uses multiple interconnected datasets representing different business functions.

| Dataset               | Description                 |
| --------------------- | --------------------------- |
| Orders                | Customer order information  |
| Order Items           | Product-level order details |
| Customers             | Customer demographics       |
| Products              | Product catalog             |
| Delivery Performance  | Delivery metrics            |
| Customer Feedback     | Ratings and sentiment       |
| Inventory             | Daily inventory records     |
| Inventory Summary     | Monthly inventory           |
| Marketing Performance | Campaign performance        |

---

# ⚙️ Tech Stack

| Technology | Purpose                     |
| ---------- | --------------------------- |
| Python     | Data Cleaning & Analysis    |
| Pandas     | Data Manipulation           |
| NumPy      | Numerical Operations        |
| SQLite     | SQL Business Analysis       |
| Power BI   | Interactive Dashboard       |
| DAX        | KPI Calculations            |
| GitHub     | Version Control & Portfolio |

---

# 🔄 Project Workflow

```text
Raw Kaggle Dataset
        │
        ▼
Google Colab
        │
        ▼
Python Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
SQL Business Analysis (SQLite)
        │
        ▼
Export Cleaned Data
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

# 🧹 Data Preparation

The following preprocessing steps were performed using Python:

* Imported multiple datasets
* Standardized column names
* Converted data types
* Removed duplicate records
* Handled missing values
* Validated primary and foreign keys
* Created analytical features
* Exported cleaned datasets for Power BI

---

# 🗄 SQL Business Analysis

Business questions answered using SQL include:

* Total Revenue
* Revenue by Category
* Top Selling Products
* Average Order Value
* Customer Analysis
* Delivery Performance
* Marketing ROI
* Inventory Analysis
* Customer Ratings
* Product Performance

SQLite was used inside Google Colab to execute analytical queries.

---

# 📊 Dashboard Pages

## 1️⃣ Executive Overview

Features:

* Total Revenue
* Total Orders
* Average Order Value
* Total Customers
* Average Rating
* Monthly Revenue Trend
* Revenue by Category
* Delivery Status
* Payment Method Analysis

---

## 2️⃣ Sales Analysis

Features:

* Revenue by Category
* Revenue by Brand
* Monthly Sales Trend
* Product Performance
* Profit Analysis
* Sales Distribution

---

## 3️⃣ Customer & Delivery Analysis

Features:

* Customer Ratings
* Sentiment Analysis
* Delivery Performance
* Delay Reasons
* Average Delivery Time
* Customer Segmentation

---

## 4️⃣ Inventory Analysis

Features:

* Inventory Trend
* Stock Received
* Damaged Inventory
* Category-wise Stock
* Inventory Health

---

## 5️⃣ Marketing Analysis

Features:

* Marketing Spend
* Revenue Generated
* ROAS
* CTR
* Conversion Rate
* Campaign Performance

---

# 📈 Key Business Insights

* Identified the highest revenue-generating product categories.
* Analyzed customer purchasing behavior.
* Evaluated delivery performance across different order statuses.
* Identified major reasons for delayed deliveries.
* Measured marketing campaign effectiveness using ROAS and CTR.
* Monitored inventory movement and damaged stock.
* Compared customer sentiment with delivery performance.

---

# 💼 Business Recommendations

Based on the analysis:

* Increase marketing investment in high-performing channels.
* Improve delivery operations in areas with higher delays.
* Focus promotions on high-margin products.
* Reduce damaged inventory through improved warehouse handling.
* Optimize inventory levels for fast-moving categories.
* Enhance customer experience by addressing recurring feedback issues.

---

# 📁 Repository Structure

```text
Blinkit-Commerce-Analysis/
│
├── README.md
│
├── notebook/
│      BlinkitSales.ipynb
│
├── dashboard/
│      blinkit.pdf
│
├── data/
│      cleaned/
│
└── screenshots/
       Executive Overview.png
       Sales Analysis.png
       Customer & Delivery.png
       Inventory Analysis.png
       Marketing Analysis.png
```

---

# 🚀 Future Enhancements

* Demand Forecasting using Machine Learning
* Customer Segmentation
* Churn Prediction
* Real-time Data Integration
* Azure Cloud Deployment
* Automated Report Refresh

---

# 👩‍💻 Author

**Anusha Geddam**

* LinkedIn: https://www.linkedin.com/in/anushageddam/

If you found this project interesting, feel free to ⭐ the repository and connect with me.
