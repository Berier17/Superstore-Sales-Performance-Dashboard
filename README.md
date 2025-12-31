# 🛒 Superstore Sales Performance Dashboard

## 📌 Project Overview
This Power BI project is an end-to-end business intelligence solution designed to analyze sales, profit, and discount trends for a retail superstore. The dashboard serves as an executive monitoring tool, enabling stakeholders to track Year-over-Year (YoY) growth, identify high-performing regions, and optimize product category strategies across the United States.

**🚀 Live Preview:** [Superstore Sales Performance Dashboard.pdf](https://github.com/user-attachments/files/24393925/Superstore.Sales.Performance.Dashboard.pdf)

## 🛠️ Tools & Technologies
* **Power BI Desktop:** Dashboard design, interactivity, and layout.
* **Power Query (M):** ETL processing to clean raw data, handle null values, and standardize column formats.
* **Data Modeling:** Established relationships between data tables to enable accurate filtering and drill-down capabilities.
* **DAX (Data Analysis Expressions):** Engineered custom measures for `Total Sales`, `Profit Margin %`, and `Average Discount`.

## 📊 Key Features & Analysis
### 1. Executive Summary
* **KPI Cards:** Instant view of critical metrics including **Total Sales**, **Total Profit**, and **Quantity Sold**.
* **Dynamic Filtering:** Slicers for **Segment** (Consumer, Corporate, Home Office) and **Ship Mode** allow users to isolate specific business units.

### 2. Regional & Geographic Performance
* **Map Visualization:** Geospatial analysis of sales distribution by State, highlighting top-performing markets (e.g., California, New York).
* **Regional Breakdown:** Bar charts comparing sales volume across West, East, Central, and South regions.

### 3. Product & Profitability Analysis
* **Category Drill-Downs:** Hierarchical analysis allowing users to drill from **Category** (Furniture, Technology) down to **Sub-Category** (Phones, Tables) to pinpoint profit drivers.
* **Discount Impact Strategy:** A scatter plot analyzing **Profit vs. Average Discount**, revealing how aggressive discounting strategies impact overall profitability in specific categories.

## 💡 Key Insights Uncovered
* **High Sales ≠ High Profit:** Certain categories (like Tables) generate high revenue but suffer from negative profit margins due to high average discounts.
* **Seasonal Trends:** The Line Chart reveals distinct seasonal spikes in Q4, suggesting the need for inventory ramp-up in October/November.
* **Shipping Efficiency:** "Standard Class" shipping accounts for the majority of orders, but "Same Day" shipping yields higher profit margins per unit.

## 📂 Project Structure
```text
/Superstore-Sales-Dashboard/
├── Superstore_Sales_Performance.pbix  # Source Power BI File
├── Data/                              # Raw Sample Superstore Dataset (CSV/XLS)
├── Screenshots/                       # Images of the dashboard for documentation
└── README.md                          # Project Documentation
