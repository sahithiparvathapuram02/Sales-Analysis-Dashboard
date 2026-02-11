# Sales-Analysis-Dashboard
**PROJECT TITLE**

Sales Anaysis Dashboard-Blinkit

**📌PURPOSE**

This project presents a comprehensive Sales Analysis Dashboard for Blinkit using Power BI. The dashboard provides actionable insights into sales performance, product trends, outlet performance, and customer purchasing patterns.

**🗂️ DATA SOURCES**

|Table|Description|
|-----|-----------|
|Blinkit_Grocery_data|Item Fat Content, Item Identifier, Item Type, OutletEstablishment Year, Outlet Identifier, Outlet Location Type, Outlet Size, Outlet Type, Item Visibility, Item Weight, Sales, Rating|

**🛠️TECH STACK**

The dashboard was built using following Tools and Technologies:
**Power BI Desktop** – Dashboard development & visualization

**Power Query** – Data cleaning & transformation

**DAX (Data Analysis Expressions)** – Calculated measures

**Excel/CSV** – Raw data sources

**🧩DASHBOARD SECTIONS**

**1. KPI Overview**

This section provides a high-level business summary:

* Total Sales

* Average Sale

* Number of Items Sold

* Average Rating

**2. Outlet Establishment Trend Analysis**

Line Chart – Outlet Establishment Year vs Sales

* Shows sales trend across years

* Helps identify growth pattern

* Analyzes business expansion impact

**3. Product Analysis Section**

**Sales by Item Type**

**Bar chart showing performance of:**

* Fruits & Vegetables 

* Snack Foods

* Household

* Frozen Foods

* Dairy

* Others

**Fat Content Analysis**

* Donut Chart – Total Sales by Fat Content

* Stacked Bar – Fat by Outlet Location

**4. Outlet Performance Analysis**

Sales by Outlet Size

* Medium – 507.9K (42.27%)

* Small – 444.79K (37.01%)

* High – 248.99K (20.72%)

Sales by Outlet Location

* Tier 3 – 472.13K

* Tier 2 – 393.15K

* Tier 1 – 336.40K

**5. Metrics by Outlet Type**
Includes:

* Total Sales

* Number of Items

* Average Sales

* Average Rating

* Item Visibility
  
**6. Interactive Filtering Capabilities**

The dashboard includes dynamic slicers for:

* Outlet Location Type

* Outlet Size

* Item Type

**🧮SAMPLE DAX MEASURES**

* Total Sales = SUM('Blinkit Grocery Data'[Sales])

* Average Sales = AVERAGE('Blinkit Grocery Data'[Sales])

* No of Items = COUNT('Blinkit Grocery Data'[Item Identifier])

* Average Rating = AVERAGE('Blinkit Grocery Data'[Rating])

**🔍KEY INSIGHTS AND FINDINGS**

* Business performance is strongest in Tier 3 locations and Supermarket Type 1 outlets, indicating strong market penetration in developing regions.

* Customers prefer regular fat products over low-fat alternatives, which may influence product stocking and promotional strategies.

* Medium-sized stores are the most efficient revenue generators, possibly due to optimal inventory and customer accessibility.

* Business expansion positively impacted revenue growth, but post-expansion performance indicates a stable growth phase.

* Customer satisfaction is stable across all outlet categories, indicating consistent service quality.

