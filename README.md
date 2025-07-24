# Pharmaceutical-Sales-Analysis
An interactive Power BI dashboard analyzing pharmaceutical sales, including revenue, profit, cost, monthly trends, and customer insights using a simulated dataset.

## Business Context
This dashboard was created to monitor pharmaceutical sales, optimize profit, and gain deeper insights into customer segmentation. It provides a clear view of revenue and profit by gender, age group, and country, helping identify underperforming regions and products.

It answers key business questions such as:
- Which age groups and genders contribute most to sales?
- How do total revenue and profit vary by month and year?
- Which countries generate lower revenue and need further investigation?

The dashboard is valuable for pharmaceutical companies, marketing teams, and finance departments. By analyzing sales performance, it supports strategic decisions such as focusing marketing efforts on specific regions, understanding why certain countries have lower sales, and improving overall profitability through better resource allocation.

To enhance analytical depth, DAX measures (e.g., COUNTROWS, CALCULATE, DIVIDE, SUMX) were used for calculations, and conditional formatting was applied to create additional visual insights. Page navigation ensures smooth transitions between report pages for a better user experience.

The dataset used is simulated and not based on real sales data. For better data modeling, the main Sales table was normalized into fact and dimension tables, a dedicated Date table was created, and proper one-to-many relationships were established across all tables.

## Key Features
1. Interactive Navigation – Bookmarks, hidden slicers, and page navigation for a cleaner, more dynamic user experience.
2. KPI Cards – Displaying key metrics such as Total Revenue, Total Cost, Total Profit, Total Quantity, and Overall Profit Margin, along with additional cards for Customer Count, Sales Transactions Count, and Average Revenue per Transaction.
3. Monthly Trend Analysis – Clustered Bar Charts showing monthly revenue, monthly profit, customer-based revenue, and medicine-level profit. Bookmarks were used to switch between these visuals efficiently due to limited dashboard space.
4. Customer & Demographic Insights:
      - Donut Charts for revenue distribution by gender and by individual customers.
      - Clustered Column Chart for revenue and profit by age groups.
5. Sales Performance Overview – Gauge Visual to analyze sales by buyer type.
6. Geographical Analysis – Treemap to visualize revenue by country.

## How It’s Built

This dashboard was developed using Power BI, leveraging its powerful data transformation, modeling, and visualization capabilities. The dataset used is simulated and prepared in Excel/CSV format before import.
Key technical aspects include:
- Data Modeling:
The original Sales table was split into fact and dimension tables for optimized performance and clarity.
A dedicated Date table was created to enable time intelligence calculations and proper relationships.
One-to-many relationships were established between fact and dimension tables to maintain data integrity and support complex queries.

- Data Transformation:
Power Query was used to clean and shape the data before loading it into the model.

- Calculations & Measures:
Advanced DAX formulas (such as COUNTROWS, CALCULATE, DIVIDE, SUMX) were implemented to compute key metrics like total revenue, profit margins, monthly trends, and customer segmentation.
Conditional formatting was applied to enhance visual interpretation and highlight important data points.

- User Experience Enhancements:
Bookmarks and page navigation were utilized to organize multiple visuals efficiently and create an interactive storytelling flow.
Slicers, including hidden slicers, enable users to filter data dynamically without cluttering the interface.

## Dashboards

