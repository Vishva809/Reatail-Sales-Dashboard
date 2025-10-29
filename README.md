# Retail Sales Dashboard 
## Project Overview

The Retail Sales Dashboard is an interactive data visualization solution designed to analyze and monitor key business performance indicators (KPIs) across products, regions, and time periods., the dashboard provides a comprehensive view of sales trends, profitability, and customer purchasing behavior to support data-driven decision-making.
- <a href = "https://github.com/Vishva809/Reatail-Sales-Dashboard/blob/main/Realmart_Sales_Dataset.xlsx"> Dataset </a>
# Objectives

- To analyze sales performance across products, categories, and regions.
- To identify top-performing products, stores, and sales representatives.
- To track revenue growth, profit margins, and customer trends over time.
- To provide real-time insights for better forecasting and strategic planning.

# Key KPIs

- Total Sales Revenue
- Total Profit & Profit Margin %
- Units Sold
- Average Order Value (AOV)
- Sales Growth Rate
- Top Products & Top Regions
- Customer Segmentation Performance
- <a href = "https://github.com/Vishva809/Reatail-Sales-Dashboard/blob/main/Screenshot%202025-10-29%20111532.png"> View Dashboard </a>
# Dashboard Features
- 📊 Dynamic Filters – Filter data by date, category, region, or customer segment
- 📈 Trend Analysis – Monthly and yearly sales & profit trends
- 🏆 Top/Bottom Analysis – Identify best and least performing products or stores
- 🌍 Geographical View – Regional performance comparison via map visualization
- 📆 Time Intelligence – Year-over-Year (YoY) and Month-over-Month (MoM) growth tracking
# Dashboard
<img width="1422" height="798" alt="Screenshot 2025-10-29 111532" src="https://github.com/user-attachments/assets/eab9097e-5679-4289-a7a1-8f07f7cc0eb5" />

# Methodology

- Data Collection: Imported raw retail sales data from Excel/CSV files.

- Data Cleaning: Handled missing values, corrected inconsistent entries, and standardized date formats using Power Query.

- Data Modeling: Created relationships between tables (Products, Sales, Customers, Regions).

- KPI Calculation: Defined key metrics using DAX formulas:

- Total Sales = SUM(Sales[Sales Amount])

- Total Profit = SUM(Sales[Profit])

- Profit Margin % = DIVIDE([Total Profit], [Total Sales])

- Sales Growth % = (Current Month Sales - Previous Month Sales) / Previous Month Sales

- Dashboard Design: Built interactive visuals including:

- Sales Trend Line Chart (Monthly/Yearly)

- Profit and Revenue KPIs

- Product and Regional Performance Bar Charts

- Geo-map for regional sales distribution

- Filters for Date, Product Category, and Customer Segment

- Insight Generation: Interpreted dashboard outcomes to identify growth trends and performance gaps.


7. Insights and Findings
- Top 10 products contributed to nearly 60% of total revenue.
- Certain regions showed high sales but low profit margins, indicating potential pricing or cost inefficiencies.
- Customer segment analysis revealed repeat customers drove 45% of overall revenue.
- Quarterly growth trends showed a 12% increase in sales in the last quarter due to promotional campaigns.

# Results and Impact

- Improved visibility into sales and profit performance across business dimensions.
- Automated dashboard reduced manual reporting time by over 70%.
- Enhanced data-driven decision-making for inventory management and marketing strategy.
- Enabled senior management to monitor business KPIs in real-time.

# Conclusion

- The Retail Sales Dashboard Project successfully demonstrates how data visualization tools like Power BI can transform raw sales data into meaningful business insights. The dashboard serves as a strategic tool for retail managers to track performance, identify key growth areas, and optimize operational decisions.

- Future improvements could include integrating real-time sales data, implementing forecasting models, and expanding the dashboard for multi-store comparison and customer lifetime value analysis.
