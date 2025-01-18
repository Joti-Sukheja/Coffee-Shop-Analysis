# Coffee Shop Analysis

## Overview
This project focuses on analyzing coffee shop sales data to uncover trends, patterns, and actionable insights. The analysis includes identifying busiest hours, top-selling items, and sales performance across different time periods. The dashboard created in Microsoft Excel uses PivotTables, charts, and slicers to deliver a clear and interactive representation of the data.

---

## Repository Structure

```plaintext
Coffee-Shop-Analysis/
│
├── data/
│   └── coffee_shop_data.xlsx       # Raw dataset for the project.
│
├── dashboard/
│   ├── coffee_shop_dashboard.xlsx  # Excel file containing the dashboard.
│   └── dashboard_screenshot.png    # Screenshot of the created dashboard.
│
├── steps-formulas/
│   └── Steps and formulas included in README.md for reference.
│
├── media/
│   └── dashboard_screenshot.png    # Media assets such as the dashboard screenshot.
│   # Optionally, add a video demonstrating the slicers.
│
├── license/
│   └── LICENSE                     # License file (e.g., MIT license).
│
└── README.md                       # Main documentation file for the project.

```
---

## Steps and Formulas

### 1. Data Cleaning
- Removed duplicate rows.
- Corrected inconsistencies in date formats.
- Standardized column names (e.g., "Order Date" → "Date").
- Checked for missing values and filled them where necessary.
    

### 2. Data Analysis
- Added calculated columns for:
    - **Hour of Order:** Extracted using `=HOUR(OrderTime)`.
    - **Month Name:** Derived from the "Date" column using `=TEXT(Date, "mmmm")`.
- Created PivotTables for:
    - Total sales and orders grouped by:
        - Hour, Day of the Week, and Month.
    - Sales breakdown by item category and item size.

### 3. Dashboard Creation
- **Slicers Used:**
    - Filters for Day of the Week, and Month.
- **Visualizations Created:**
    - **Bar charts:** Orders per weekday.
    - **Pie chart:** Size-wise distribution of items sold.
    - **Line chart:** hourly sales trends.

---

## Tools Used
- Microsoft Excel for data cleaning and analysis.
- PivotTables and PivotCharts for summarizing data.
- Slicers for dynamic and interactive filtering.

---

## Key Insights
- **Peak Hours:** Orders peak from 7 AM to 10 AM.
- **Sales Trends:** Saturdays have the lowest sales; Fridays are the busiest.
- **Popular Product:** Barista Espresso leads in revenue.
- **Top Locations:** Astorle and Hell's Kitchen top the sales chart.

---

## Getting Started

### Dataset:
- Open [data/Coffee_Shop_Sales.xlsx](./data) to explore the raw dataset used in the analysis.

### Dashboard:
- Open [dashboard/coffee_shop_(excel file).xlsx](./dashboard) to interact with the dashboard. Use slicers for dynamic filtering and visualization.

### Steps and Formulas:
- Refer to the **Steps and Formulas** section above for details on data cleaning, analysis, and dashboard creation.

---

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.


