Warehouse Management System Dashboard (Power BI)

Project Overview
This project presents an interactive Warehouse Management System dashboard built using Microsoft Power BI. 
The dashboard provides insights into inventory levels, warehouse utilization, order trends, and product performance, 
helping stakeholders monitor warehouse operations and make data-driven decisions.

The goal of this project is to demonstrate data modeling, business intelligence reporting, and interactive dashboard 
design using Power BI.

Key Insights Delivered
• Warehouse utilization monitoring
• Inventory distribution across warehouses
• Low stock alerts for inventory management
• Revenue contribution by product category
• Order status distribution

Key DAX Measures

Revenue = SUMX( OrderDetails, OrderDetails[Quantity] *
OrderDetails[UnitPrice] )

Total Inventory = SUM(Inventory[StockQty])

Warehouse Utilization = DIVIDE( SUM(Inventory[StockQty]),
SUM(Warehouses[Capacity]) )

Low Stock = IF( Inventory[StockQty] < Inventory[ReorderLevel], “Yes”,
“No” )

Tools & Technologies - Microsoft Power BI - DAX (Data Analysis
Expressions) - Data Modeling - Power Query - Microsoft Excel

Skills Demonstrated - Data Visualization - Business Intelligence
Reporting - Data Modeling - Dashboard Development - KPI Monitoring -
Supply Chain Analytics - Inventory Analysis

Business Value This dashboard helps warehouse managers and
stakeholders: - Track inventory levels across warehouses - Identify
products requiring restocking - Monitor warehouse capacity utilization -
Analyze product demand trends - Improve operational decision-making

Author 
Saurabh Tripathi

• Top-selling products analysis
• Monthly order trends
\\\\
