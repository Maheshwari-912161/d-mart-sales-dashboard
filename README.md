# d-mart-sales-dashboard
This repository contains a comprehensive Power BI Project that analyzes D-Mart's sales performance using interactive visualizations. The dashboard integrates order and transaction data to track key business metrics, identify trends, and uncover actionable insights.
After downloadding the Datasets 

Data Modelling
Both tables are connected using the Order ID with cardinality of many to one relationship
And a new measure of Amount Order Value = Amount/Quantity


Data Visualisation

Switch to the Report View.
Add KPIs:
Use Card Visualizations to display:
Total Sales: ₹438K
Average Order Value: ₹121K
Total Quantity Sold: 5615
Total Profit: ₹37K

Create Charts:
Bar Chart:
Amount by State: State on the X-axis, Amount on the Y-axis.
Profit by Sub-Category: Sub-Category on the X-axis, Profit on the Y-axis.
Top Customers by Amount: Sort by Amount and display as a ranked bar chart.
Donut Chart:
Quantity by Category: Category and Quantity.
Quantity by Payment Mode: Payment Mode and Quantity.
Trend Chart:
Profit by Month: Use a bar chart with Order Date (Month) on the X-axis and Profit on the Y-axis.
Enable Filters:
Add Slicers for:
Quarter: Derived from Order Date using DAX or Power BI's time intelligence.
State: Dropdown slicer based on State column.

Key Insights 
Analyze Patterns:
Identify the best-performing states based on total sales.
Spot trends in profit over months.
Assess which product categories and payment modes are most popular.

Tools& Skills
Power BI Desktop
Dat Modelling and Relationships
DAX Calculatiions
Data Visualisation and Design
Interactive slicers and Filters
