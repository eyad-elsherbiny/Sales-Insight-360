# 📊 Sales Insight 360

## 🎯 Project Overview

This project involves a comprehensive data analysis of sales records to evaluate financial performance, operational efficiency, and customer logistics. The final output is an interactive Excel Dashboard that visualizes key metrics such as Net Profit, Gross Sales, and Profit Margins, allowing stakeholders to make data-driven decisions.

## 🗂️ Data Structure

The analysis is based on a transactional dataset containing sales information. The workflow transforms raw data into a structured "Calculations" layer, which then feeds the visual dashboard.

**Key Data Points Processed:**

- **Financials:** Gross Sales, Discounts, Net Sales, COGS (Cost of Goods Sold), and Net Profit.
    
- **Operations:** Order counts and product distribution.
    
- **Logistics:** Customer segmentation and shipping logic.
    

## 🔄 The Process: From Raw Data to Dashboard

This project followed a structured data analysis pipeline:

### 🧹 1. Data Cleaning & Preparation

Before analysis, the raw dataset underwent a cleaning process to ensure accuracy:

- **Duplicate Removal:** Checked for and removed duplicate transaction IDs.
    
- **Data Type Formatting:** Ensured dates, currency, and numerical values were formatted correctly for calculation.
    
- **Missing Values:** Addressed null values in critical columns (e.g., filling missing region data or excluding incomplete records).
    

### 🧮 2. Data Modeling & Calculations

A dedicated staging sheet (`Calculations`) was created to aggregate data and perform row-level computations. This prevented the dashboard from slowing down by separating the heavy lifting from the visualization layer.

**Key Formulas & KPIs Created:**

- **Net Sales:** Calculated as `Gross Sales - Total Discount`.
    
- **Net Profit:** Derived from `Net Sales - Total Cost`.
    
- **Profit Margin %:** Calculated as `(Net Profit / Net Sales) * 100` to measure efficiency.
    
- **Aggregations:** Used `SUMIF` and Pivot Table logic to group data by:
    
    - Financial Overview (Sales vs. Profit)
        
    - Products & Operations (Order Volume)
        
    - Customer & Logistics (Regional performance)
        

### 🎨 3. Dashboard Design & Visualization

The final step involved building the visual interface. The dashboard links directly to the calculated tables to provide dynamic updates.

_Above: A preview of the interactive dashboard in action._

**Visual Elements Include:**

- **KPI Cards:** Displaying high-level metrics (e.g., Total Net Profit: ~$49k, Total Gross Sales: ~$621k).
    
- **Trend Analysis:** Charts tracking sales performance over time.
    
- **Category Breakdown:** Visualizing which products drive the most revenue.
    
- **Slicers:** Interactive filters allowing users to drill down by Year, Region, or Product Category.
    

## 💡 Key Insights

Based on the analysis of the dataset:

- **Revenue vs. Cost:** The project tracks the relationship between the ~$621k in Gross Sales and the costs involved, highlighting a Net Profit of approximately $49k.
    
- **Discount Impact:** Analysis of the ~$137k in total discounts helps determine if promotional pricing strategies are eroding margins too heavily.
    
- **Volume:** Operational metrics track the flow of orders to identify peak periods and logistical bottlenecks.
    

## 🧰 Tools Used

- **Microsoft Excel:**
    
    - Pivot Tables
        
    - Advanced Formulas
        
    - Data Validation
        
    - Slicers & Charts
        

## ⚡ How to Use This Repository

1. **Download:** Clone the repository or download the `analysis_dashboard.xlsx` file.
    
2. **Open:** Open the file in Microsoft Excel.
    
3. **Interact:** Use the Slicers on the "Dashboard" sheet to filter the data.
    
4. **Review:** Check the "Calculations" sheet to see the logic behind the metrics.
    

## 🚀 Future Improvements

- Integration with Power BI for real-time web-based reporting.
    
- Adding "Return Rate" analysis to the Logistics section.
    
- Forecasting future sales using moving averages.
    

_Author: Eyad Adel_
