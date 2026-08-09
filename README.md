# 🛍️ Customer Shopping Behavior Analysis

<p align="center">
  <b>End-to-End Data Analytics Project using Python, SQL & Power BI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/SQL-Data%20Analysis-orange?logo=mysql" alt="SQL">
  <img src="https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-yellow?logo=powerbi" alt="Power BI">
  
</p>

---

## 📌 Project Overview

**Customer Shopping Behavior Analysis** is an end-to-end Data Analytics project developed to understand customer purchasing patterns, spending behavior, product preferences, demographics, and shopping trends.

The project combines **Python, SQL, and Power BI** to transform customer shopping data into meaningful business insights.

Python was used for data cleaning, preprocessing, and exploratory data analysis. SQL was used to perform business-focused analysis and extract key insights. Power BI was used to develop an interactive dashboard for KPI tracking, data visualization, and business reporting.

The project demonstrates a complete analytics workflow from raw data preparation to business insights and data-driven recommendations.

---

## 🎯 Business Objectives

The main objectives of this project are:

- Analyze customer purchasing behavior and spending patterns.
- Identify high-performing product categories.
- Understand customer demographics and preferences.
- Analyze customer purchase frequency.
- Evaluate the impact of discounts on purchasing behavior.
- Compare subscribed and non-subscribed customers.
- Analyze customer ratings and payment preferences.
- Identify potential high-value customer segments.
- Build an interactive Power BI dashboard.
- Generate actionable business insights.
- Support data-driven business decision-making.

---

## 🔄 Project Workflow

```text
                    Customer Shopping Dataset
                              │
                              ▼
                    Data Cleaning & Preparation
                              │
                              ▼
                    Exploratory Data Analysis
                              │
                              ▼
                    Python-Based Analysis
                              │
                              ▼
                     SQL Business Analysis
                              │
                              ▼
                      KPI & Insight Generation
                              │
                              ▼
                     Power BI Dashboard
                              │
                              ▼
                 Business Insights & Recommendations
```

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **Python** | Data cleaning, preprocessing and exploratory analysis |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical operations |
| **Matplotlib** | Data visualization |
| **SQL** | Business analysis and data querying |
| **Power BI** | Interactive dashboard and KPI reporting |
| **CSV** | Dataset storage |

---

# 🧹 Data Cleaning & Preparation

Data cleaning and preparation were performed using **Python and Pandas** before conducting further analysis.

### Data Preparation Activities

- Loaded and inspected the dataset.
- Checked dataset structure and dimensions.
- Reviewed column names and data types.
- Identified missing values.
- Checked for duplicate records.
- Validated numerical and categorical fields.
- Cleaned and prepared the dataset.
- Standardized data where required.
- Prepared the cleaned dataset for further analysis.

---

# 🐍 Python Data Analysis

Python was used as the primary analytical layer for data preparation and exploratory data analysis.

### Analysis Performed

- Dataset overview and statistical summary.
- Customer demographic analysis.
- Purchase amount analysis.
- Product category analysis.
- Customer spending behavior.
- Purchase frequency analysis.
- Discount usage analysis.
- Subscription analysis.
- Customer rating analysis.
- Payment method analysis.
- Data visualization and trend identification.

### Python Libraries

```python
import pandas as pd
import numpy as np
```

---

# 🗄️ SQL Business Analysis

SQL was used to perform structured business analysis and extract meaningful insights from the customer shopping dataset.

### SQL Analysis Areas

- Total sales analysis.
- Average purchase amount.
- Sales by product category.
- Customer purchase frequency.
- Customer spending analysis.
- Subscription behavior.
- Discount usage.
- Gender-based analysis.
- Age-group analysis.
- Payment method analysis.
- Customer rating analysis.
- Product category performance.
- Customer segmentation.

### Example SQL Query

```sql
SELECT
    Category,
    SUM(Purchase_Amount) AS Total_Sales,
    AVG(Purchase_Amount) AS Average_Purchase
FROM customer_shopping
GROUP BY Category
ORDER BY Total_Sales DESC;
```

This query identifies product categories based on total sales and average purchase amount.

---

# 📊 Power BI Dashboard

An interactive **Power BI dashboard** was developed to present the analytical findings in a clear and business-friendly format.

The dashboard combines KPIs, charts, filters, and visualizations to provide a comprehensive view of customer shopping behavior.

## 📌 Key Performance Indicators

- **Total Customers**
- **Total Sales**
- **Average Purchase Amount**
- **Average Customer Rating**
- **Purchase Frequency**
- **Subscription Rate**

## 📈 Dashboard Analysis

The dashboard provides insights into:

- Customer demographics
- Sales performance
- Product categories
- Customer spending
- Purchase frequency
- Subscription status
- Discount usage
- Payment methods
- Customer ratings
- Customer segmentation

Interactive filters allow users to explore customer behavior from different customer and product perspectives.

---

# 🔍 Key Insights

The analysis provides a detailed understanding of customer shopping behavior.

### 👥 Customer Behavior

Customer purchasing patterns were analyzed based on demographics, spending behavior, purchase frequency, subscription status, and shopping preferences.

### 🛒 Product Performance

Product categories were analyzed to identify stronger-performing categories and understand customer demand patterns.

### 💰 Customer Spending

Customer purchase amounts were analyzed to identify spending patterns and potential high-value customer segments.

### 🎯 Customer Segmentation

Customers were analyzed based on purchasing behavior, spending, frequency, and engagement to identify meaningful customer groups.

### 🏷️ Discount Behavior

Discount usage was analyzed to understand customer response to promotional offers and support better discount strategies.

### 🔄 Subscription Behavior

Subscribed and non-subscribed customers were compared to understand differences in purchasing behavior and identify customer retention opportunities.

### 💳 Payment Preferences

Payment method analysis was performed to understand commonly preferred payment options among customers.

---

# 📈 Dashboard Preview

The Power BI dashboard provides an interactive overview of customer shopping behavior, sales performance, customer segments, and key business metrics.

> **Note:** If your dashboard screenshot has a different filename, replace the filename below with the exact filename uploaded to your GitHub repository.

![Customer Shopping Behavior Dashboard](Customer%20Behavior%20Analysis%20Dashboard_Screenshot.png)

---

# 📂 Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer Behavior Analysis Dashboard_Screenshot.png
├── Customer Behavior Analysis.pbix
├── Customer_Shopping_Behavior_Analysis_In_Python.ipynb
├── Customer_shopping_behavior_analysis.sql
└── README.md
```

---

# 📚 Project Files

| File | Description |
|------|-------------|
| `Customer Behavior Analysis.pbix` | Interactive Power BI dashboard |
| `Customer_Shopping_Behavior_Analysis_In_Python.ipynb` | Python data cleaning, EDA and analysis |
| `Customer_shopping_behavior_analysis.sql` | SQL business analysis queries |
| `Customer Behavior Analysis Dashboard_Screenshot.png` | Power BI dashboard screenshot |
| `README.md` | Complete project documentation |

---

# 🧠 Skills Demonstrated

## Data Analytics

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Customer Behavior Analysis
- Sales Analysis
- Customer Segmentation
- Statistical Analysis
- Business Analysis

## Technical Skills

- Python
- Pandas
- NumPy
- Matplotlib
- SQL
- Power BI
- Data Visualization
- Dashboard Development
- KPI Analysis

## Business Intelligence

- Business Question Formulation
- Business Requirement Analysis
- Customer Insights
- Trend Analysis
- Performance Analysis
- Strategic Recommendations
- Data-Driven Decision Making

---

# 📊 Data Analytics Concepts Used

- Exploratory Data Analysis
- Descriptive Analysis
- Customer Segmentation
- Sales Performance Analysis
- Trend Analysis
- KPI Development
- Data Visualization
- Business Intelligence
- Customer Behavior Analysis
- Data-Driven Decision Making

---

# 📌 Project Outcome

This project demonstrates a complete **end-to-end Data Analytics workflow**, starting from raw customer shopping data and progressing through:

**Data Cleaning → Exploratory Analysis → SQL Analysis → KPI Development → Power BI Dashboard → Business Insights → Recommendations**

The integration of **Python, SQL, and Power BI** demonstrates practical skills in data analysis, business intelligence, data visualization, dashboard development, and business decision-making.

The final solution converts raw customer shopping data into structured insights that can help businesses better understand their customers, improve marketing strategies, optimize sales performance, and strengthen customer retention.

---

# 🚀 Future Enhancements

The project can be further enhanced by:

- Developing advanced customer segmentation using Machine Learning.
- Performing Customer Lifetime Value (CLV) analysis.
- Predicting customer churn.
- Developing purchase prediction models.
- Building a product recommendation system.
- Performing sales forecasting.
- Adding automated Power BI data refresh.
- Integrating additional customer and transaction datasets.
- Developing a real-time analytics dashboard.

---

## ⭐ Project Highlights

- End-to-End Data Analytics Project
- Python-Based Data Cleaning & EDA
- SQL Business Analysis
- Interactive Power BI Dashboard
- Customer Behavior Analysis
- Sales & Product Performance Analysis
- Customer Segmentation
- Business Insights & Recommendations
- Data-Driven Decision Making

---
# 👩‍💻 Author

## Greeshma R Krishnan

Python • SQL • Power BI • Excel • Data Visualization

---



---

⭐ **If you find this project useful, feel free to explore the repository.**
