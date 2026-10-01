# E-Commerce Sales Analysis & Power BI Dashboard

An end-to-end **E-Commerce Sales Analysis** project using **Python and Power BI** to understand sales performance, customer behavior, regional performance, payment methods, delivery efficiency, and customer satisfaction.

The project combines **data analysis in Python** with an interactive **Power BI dashboard** to turn transactional data into clear business insights.

---

## 📌 Project Overview

The dataset contains:

- **5,000 orders**
- **989 unique customers**
- Multiple product categories
- Multiple regions
- Different payment methods
- Delivery and customer rating information

The analysis focuses on:

- Revenue and order performance
- Monthly sales trends
- Product category performance
- Regional performance
- Average Order Value (AOV)
- Customer behavior
- Quantity vs. Revenue
- Discount analysis
- Payment method usage
- Delivery performance
- Customer ratings
- Correlation between numerical variables

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **Microsoft Power BI**
- **DAX**
- **Power Query**

---

## 📊 Python Analysis

The Jupyter Notebook (`ecomercy.ipynb`) covers the main analytical stages of the project:

### 1. Exploratory Data Analysis
Initial exploration of the dataset, structure, variables, and distributions.

### 2. Sales Performance
Analysis of:

- Total Revenue
- Total Orders
- Revenue trends over time
- Monthly Revenue and Growth

### 3. Product Analysis
Comparison of:

- Revenue by Product Category
- Average Order Value (AOV) by Category

### 4. Regional Analysis
Analysis of revenue performance across regions.

### 5. Customer & Order Analysis
Exploration of:

- Customer revenue
- New vs. returning customers
- Order quantity
- Quantity vs. Revenue

### 6. Discount Analysis
Investigation of discount behavior and its relationship with revenue per order.

### 7. Delivery & Customer Satisfaction
Analysis of:

- Average Delivery Days
- Delivery performance by region
- Customer ratings
- Relationship between delivery time and rating

### 8. Payment Analysis
Comparison of payment methods based on order usage.

### 9. Correlation Analysis
Correlation analysis between key numerical variables, including:

- Unit Price and Revenue
- Quantity and Revenue
- Delivery Days and Customer Rating

### 10. Key Insights & Business Recommendations
The notebook summarizes the main findings and highlights areas that may deserve further business investigation.

---

## 📈 Power BI Dashboard

The Power BI dashboard presents the analysis through interactive KPIs and visualizations.

### Key KPIs

- **Total Revenue**
- **Total Orders**
- **Total Customers**
- **Average Order Value**
- **Average Delivery Days**
- **Average Customer Rating**

### Main Visualizations

- **Monthly Revenue Trend**
- **Revenue by Product Category**
- **Revenue by Region**
- **Average Customer Rating by Region**
- **Average Delivery Time by Region**
- **Orders by Payment Method**
- **Quantity vs. Revenue**

### Interactive Filters

The dashboard includes slicers for:

- Product Category
- Region
- Payment Method

---

## 🔎 Key Findings

Based on the full-dataset analysis:

- **Total Revenue:** approximately **5.11 million**
- **Total Orders:** **5,000**
- **Unique Customers:** **989**
- **Average Order Value:** approximately **1.02K**
- **Average Delivery Time:** approximately **6.12 days**
- **Average Customer Rating:** approximately **2.97 / 5**

### Product Performance

- **Electronics** generated the highest total revenue at approximately **1.83 million**.
- **Clothing** generated approximately **1.53 million** in revenue.
- **Beauty** recorded the highest Average Order Value among the analyzed product categories at approximately **1,059**.

### Regional Performance

- The **West** region generated the highest revenue at approximately **1.35 million**.
- The **South** region had the highest average delivery time at approximately **6.17 days**.

### Payment Behavior

- **Card** was the most frequently used payment method, with approximately **2,270 orders**.

### Correlation Findings

- **Unit Price and Revenue:** positive correlation of approximately **0.68**
- **Quantity and Revenue:** positive correlation of approximately **0.62**
- **Delivery Days and Customer Rating:** very weak negative correlation of approximately **-0.02**

> Correlation indicates association between variables and does not by itself establish causation.

---

## 💡 Business Recommendations

The analysis highlights several areas for further investigation:

1. Explore the factors behind the strong revenue contribution from **Electronics** and **Clothing**.
2. Investigate why **Beauty** shows a higher Average Order Value.
3. Examine the drivers of strong revenue performance in the **West** region.
4. Review delivery performance in the **South** region and identify operational improvement opportunities.
5. Explore how **order quantity** and higher-value purchases relate to revenue.
6. Review the relationship between **discounts** and revenue per order.
7. Monitor **payment method usage**, particularly Card payments.
8. Continue monitoring customer satisfaction and its relationship with operational metrics.

---

## 📁 Project Structure

```text
ecommerce-sales-powerbi-dashboard/
│
├── README.md
├── ecomerce.pbix
├── ecomercy.ipynb
└── screenshots/
    └── dashboard.png
```

> Add the cleaned dataset to the repository only when it is appropriate and permitted to share publicly.

---

## 📷 Dashboard Preview

Add your Power BI dashboard screenshot here:

```markdown
![E-Commerce Sales Dashboard](dashboardscreenshots)
```

---

## 🎯 Project Objective

The goal of this project was to practice an end-to-end data analytics workflow:

**Data Exploration → Data Analysis → Insight Generation → Power BI Visualization → Business Recommendations**

It demonstrates the use of Python for analytical work and Power BI for interactive business reporting.

---

## 👩‍💻 Author

**Nada**

Data Analytics | Power BI | Python

---

⭐ Thanks for checking out the project!
