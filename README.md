# 📊 Business Sales Performance Analytics

> **Future Interns — Data Science & Analytics Internship | Task 1**

![Executive Dashboard](screenshots/executive_sales_dashboard.png)

A complete business sales analytics project that transforms raw Superstore sales data into actionable insights through data cleaning, exploratory analysis, profitability analysis, trend analysis, and an executive-style dashboard.

---

## 📌 Project Overview

This project analyzes historical sales transactions to understand:

* Revenue performance
* Profitability
* Product performance
* Category performance
* Regional performance
* Sales trends over time
* Loss-making products
* Business growth opportunities

The objective is to convert raw transactional data into **clear, data-driven business recommendations**.

---

## 🎯 Business Objectives

The analysis focuses on answering key business questions:

1. Which products generate the highest revenue?
2. Which products generate the highest profit?
3. Which categories perform best?
4. Which regions contribute the most revenue and profit?
5. How do sales change over time?
6. Which products generate negative profit?
7. Where should the business focus its growth efforts?
8. How can profitability be improved?

---

## 🛠️ Tools & Technologies

| Technology       | Purpose                            |
| ---------------- | ---------------------------------- |
| Python           | Data analysis and processing       |
| Pandas           | Data cleaning and aggregation      |
| NumPy            | Numerical operations               |
| Matplotlib       | Data visualization                 |
| Seaborn          | Exploratory visualization          |
| Jupyter Notebook | Analysis workflow                  |
| CSV              | Data storage and processed outputs |

---

## 🔄 Project Workflow

```text
Raw Sales Data
      ↓
Data Inspection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
KPI Analysis
      ↓
Product Analysis
      ↓
Category Analysis
      ↓
Regional Analysis
      ↓
Time-Series Analysis
      ↓
Profitability Analysis
      ↓
Business Insights
      ↓
Executive Dashboard
      ↓
Recommendations
```

---

## 📊 Executive Dashboard

The project includes an executive-style dashboard covering key business performance indicators, sales trends, category performance, regional profitability, and top products.

![Executive Sales Dashboard](screenshots/executive_sales_dashboard.png)

---

## 💡 Business Insights

The analysis was converted into an executive-friendly insights page highlighting the strongest categories, regions, growth periods, and profitability risks.

![Business Insights](screenshots/business_insights.png)

The insights are generated directly from the analytical results, ensuring that recommendations are based on the underlying sales data rather than manually entered observations.


## 📈 Key Analysis Areas

### Revenue & KPI Analysis

The project calculates:

* Total Sales
* Total Profit
* Total Orders
* Total Quantity Sold
* Average Order Value
* Overall Profit Margin

### Product Performance

Products are evaluated based on:

* Total revenue
* Total profit
* Top-selling products
* Most profitable products
* Loss-making products

### Category Performance

Each product category is compared using:

* Sales
* Profit
* Profit margin

### Regional Performance

Regions are evaluated based on:

* Revenue contribution
* Profit contribution
* Profit margin

### Time-Based Analysis

The project analyzes:

* Monthly sales trends
* Yearly sales performance
* Sales growth
* Profit growth

---

## 💡 Business Insights

The analysis identifies:

* Highest-performing categories
* Most profitable categories
* Strongest regions
* Weakest regions by profitability
* Highest-revenue products
* Most profitable products
* Loss-making products
* Strongest sales-growth periods

These findings are used to develop actionable recommendations rather than simply presenting descriptive charts.

---

## 🎯 Business Recommendations

Based on the analytical findings, recommended actions include:

### 1. Prioritize High-Performing Products

Maintain adequate inventory and marketing support for products that consistently generate strong revenue and profit.

### 2. Review Loss-Making Products

Investigate products with negative profitability to determine whether pricing, discounts, shipping costs, or product costs are affecting margins.

### 3. Focus on Profitable Regions

Prioritize expansion and customer acquisition in regions that demonstrate strong revenue together with healthy profitability.

### 4. Optimize Low-Margin Sales

Products and categories with high revenue but comparatively low margins should be reviewed for pricing and discount optimization.

### 5. Use Sales Trends for Planning

Historical sales patterns can support inventory planning, promotional timing, and resource allocation.

---

## 📁 Project Structure

```text
FUTURE_DS_01/
│
├── data/
│   ├── raw/
│   │   └── Sample - Superstore.csv
│   │
│   ├── processed/
│   │   └── superstore_cleaned.csv
│   │
│   └── analysis/
│       ├── category_performance.csv
│       ├── regional_performance.csv
│       ├── yearly_performance.csv
│       ├── top_products.csv
│       ├── top_profit_products.csv
│       ├── loss_making_products.csv
│       └── monthly_trend.csv
│
├── notebooks/
│   └── sales_analysis.ipynb
│
├── dashboard/
│
├── report/
│
├── screenshots/
│   ├── executive_sales_dashboard.png
│   ├── monthly_sales_trend.png
│   ├── monthly_sales_trend_over_time.png
│   ├── sales_by_category.png
│   ├── sales_by_region.png
│   ├── profit_by_category.png
│   ├── profit_by_region.png
│   ├── top_10_products.png
│   ├── top_10_profit_products.png
│   ├── bottom_10_profit_products.png
│   └── yearly_sales_trend.png
│
└── README.md
```

---

## 📓 Analysis Notebook

The complete analysis workflow is available in:

```text
notebooks/sales_analysis.ipynb
```

The notebook includes data loading, cleaning, feature engineering, exploratory analysis, KPI calculations, business analysis, visualizations, and insight generation.

---

## 📊 Dataset

The project uses the **Superstore Sales Dataset**, containing transactional information including:

* Orders
* Customers
* Products
* Categories
* Regions
* Sales
* Quantity
* Discounts
* Profit
* Order dates
* Shipping information

The dataset is used strictly for analytical and educational purposes within this internship project.

---

## 🚀 Outcome

This project demonstrates an end-to-end **Data Science & Analytics workflow**, from raw transactional data to business-oriented insights and an executive dashboard.

The final objective is not only to understand **what happened**, but also to identify **where the business can improve and grow**.

---

## 👩‍💻 Author

**Chitra Saravanan**

MCA — VIT Vellore

Data Science & Analytics | Python | SQL | Data Visualization | Machine Learning
