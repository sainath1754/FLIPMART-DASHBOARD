# Flipmart Sales Dashboard

## Project Overview
This project presents a comprehensive sales dashboard for Flipmart, providing insights into various aspects of the company's sales performance. The dashboard is built using Microsoft Power BI, leveraging DAX (Data Analysis Expressions) and Power Query for data modeling and transformation.

## Dashboard Metrics
- **Total Sales**: 12.64M
- **Total Profit**: 1.47M
- **Total Quantity**: 178K
- **Transactions**: 51.29K

## Features
1. **Date Range Selection**: Users can select order dates between 01-01-2019 and 31-12-2022.

2. **Shipping Mode Filter**: Options include First Class, Same Day, Second Class, and Standard Class.

3. **Total Sales by Shipping Mode**: Visualized as a bar chart.

4. **Sum of Sales by Month and Segment**: Line graph showing trends for Consumer, Corporate, and Home Office segments.

5. **Sum of Sales by Country**: World map visualization of sales distribution.

6. **Sum of Profit by Category**: Pie chart showing profit distribution among Technology (45.23%), Office Supplies (35.34%), and Furniture (19.43%).

7. **Top 5 Sales by Sub-Category**: 
   - Bookcases: $14,66,572.24
   - Chairs: $15,01,681.76
   - Copiers: $15,09,436.27
   - Phones: $17,06,824.14
   - Storage: $11,26,812.97
   - Total: $73,11,327.39

## Data Structure
The dashboard is based on a dataset with the following columns:
Row ID, Order ID, Order Date, Ship Date, Shipping Mode, Customer ID, Customer Name, Segment, City, State, Country, Region, Market, Product ID, Category, Sub-Category, Product Name, Sales, Shipping Cost, Quantity, Profit, Order Priority

## Technical Details
- **Built with**: Microsoft Power BI
- **Data Modeling**: Utilizes DAX (Data Analysis Expressions) for creating calculated columns, measures, and tables
- **Data Transformation**: Employs Power Query for data cleaning, shaping, and integration
- **Data Source**: Database containing 51,290 rows of sales data

## Usage
This dashboard provides a quick overview of Flipmart's sales performance, allowing users to:
- Analyze sales trends over time
- Compare performance across different segments and categories
- Identify top-performing products and sub-categories
- Examine geographical distribution of sales
- Assess the impact of different shipping modes on sales

## Development and Maintenance
- **Power BI Desktop**: Used for dashboard development and updates
- **DAX**: For creating advanced calculations and custom measures
- **Power Query**: For data transformation and preparation

## Deployment
- (Specify how the dashboard is published and shared, e.g., Power BI Service, Power BI Report Server, etc.)

## Future Enhancements
Potential areas for dashboard improvement:
1. Add more interactive filters (e.g., by product category, region)
2. Incorporate predictive analytics using Power BI's forecasting capabilities
3. Include year-over-year comparison features using DAX time intelligence functions
4. Add drill-down capabilities for deeper analysis
5. Implement row-level security for data access control

## Troubleshooting
For common issues:
1. Refresh data source connections
2. Check DAX formulas for errors
3. Verify Power Query transformations
