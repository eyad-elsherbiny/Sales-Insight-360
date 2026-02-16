# 📊 Sales Insight 360 🎯

A comprehensive sales analysis project that transforms raw transactional data into actionable business insights through an **interactive Excel dashboard**.

---

## 🗂️ Dataset Overview

The analysis is based on a transactional dataset containing sales records. The workflow transforms raw data into a structured **Calculations layer**, which feeds the interactive dashboard.

**Key Data Points Processed:**

|Category|Metrics|
|---|---|
|**Financials**|Gross Sales, Discounts, Net Sales, COGS, Net Profit|
|**Operations**|Order Counts, Product Distribution|
|**Logistics**|Customer Segmentation, Shipping Logic|

---

## 🔄 Analysis Workflow

### 1. Data Cleaning & Preparation

- **Duplicate Removal:** Ensured no repeated transaction IDs.
    
- **Data Type Formatting:** Standardized dates, currency, and numeric fields.
    
- **Missing Values:** Addressed nulls by filling critical columns or excluding incomplete records.
    

### 2. Data Modeling & Calculations

A dedicated **Calculations sheet** aggregates data and performs row-level computations, keeping the dashboard fast and responsive.

**Key Formulas & KPIs:**

- **Net Sales:** `Gross Sales - Total Discounts`
    
- **Net Profit:** `Net Sales - Total Cost`
    
- **Profit Margin %:** `(Net Profit / Net Sales) * 100`
    

**Aggregations:**

- Financial Overview: Sales vs. Profit
    
- Products & Operations: Order Volume
    
- Customer & Logistics: Regional Performance
    

---

### 3. Dashboard Design & Visualization

The dashboard links directly to the calculated tables to provide **dynamic updates**.

**Visual Elements Include:**

- **KPI Cards:** Total Net Profit (~$49k), Total Gross Sales (~$621k)
    
- **Trend Analysis:** Charts tracking sales over time
    
- **Category Breakdown:** Top-performing products
    
- **Slicers:** Filter by Year, Region, or Product Category
    

<!-- Replace with your actual image path -->

---

## 💡 Key Insights

- **Revenue vs. Cost:** Gross Sales ~$621k, Net Profit ~$49k.
    
- **Discount Impact:** Total discounts ~$137k—analyzed for margin erosion.
    
- **Operational Volume:** Identified peak periods and potential logistical bottlenecks.
    
- **High-Performing Regions & Products:** Quickly highlighted using interactive filters.
    

---

## 🧰 Tools & Techniques

- **Microsoft Excel:** Pivot Tables, Advanced Formulas, Data Validation
    
- **Visualizations:** KPI Cards, Trend Charts, Slicers
    
- **Data Prep:** Handling duplicates, missing values, and formatting
    

---

## ⚡ How to Use This Repository

1. **Download:** Clone or download `analysis_dashboard.xlsx`.
    
2. **Open:** Launch the file in Microsoft Excel.
    
3. **Interact:** Use the slicers on the Dashboard sheet to filter data dynamically.
    
4. **Review:** Explore the Calculations sheet to understand the logic behind metrics.
    

---

## 🚀 Future Improvements

- **Power BI Integration:** Real-time, web-based reporting.
    
- **Return Rate Analysis:** Extend the Logistics section.
    
- **Sales Forecasting:** Implement moving averages and predictive modeling.
    
- **Automation:** Auto-refresh dashboard with new transactional data.
    

---

## 💼 Business Impact

This dashboard enables stakeholders to:

- Make **data-driven decisions** on pricing, promotions, and operations
    
- Optimize **discount strategies** to improve profit margins
    
- Identify **high-margin products and regions** for strategic focus
    
- Detect **peak operational periods** to streamline logistics
    

---

**Author:** Eyad Adel
