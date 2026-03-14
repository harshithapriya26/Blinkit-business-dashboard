# Blinkit-business-dashboard
This project focuses on analyzing Blinkit retail sales data and transforming raw data into meaningful business insights using Microsoft Power BI. The dashboard provides a comprehensive view of product performance, outlet efficiency, customer satisfaction, and sales trends.

Tools & Technologies Used : Microsoft Power BI Power Query (Data Cleaning & Transformation) DAX (Data Analysis Expressions) Data Modeling Interactive Dashboard Design

Project Workflow :

1.Data Cleaning & Transformation : Data was cleaned and transformed using Power Query to ensure accuracy and consistency. The following steps were performed: Removed duplicate records Handled missing values Standardized column formats Corrected inconsistent category names Converted data types for proper analysis

Calculated Columns : Several calculated columns were created to enhance the analysis: Sales per Kg – Calculates sales generated per kilogram of product Years of Operation – Calculates the number of years an outlet has been operating Profit Margin – Measures profitability based on revenue and cost (if cost data is available)

Lookup Tables : To improve the data model, separate lookup tables were created: Item Details – Product name, category, and weight information Item Nutrition – Nutritional attributes such as fat content Outlet Information – Outlet type, size, and establishment year

Dashboard Visualizations : The dashboard includes multiple visualizations to analyze business performance: Line Chart Displays monthly or yearly sales trends to track sales growth over time. Pie / Donut Chart Shows sales distribution based on fat content (Regular vs Low Fat). Funnel Chart Analyzes sales performance across different outlet types. Gauge Chart Displays sales performance compared to target sales. Scatter Chart Shows the relationship between item visibility and sales performance. Matrix / Table Lists the Top 10 products based on sales and customer ratings.

Business Questions Answered : The dashboard helps answer key management questions: Which product categories contribute most to overall sales? How does fat content (Regular vs Low Fat) influence sales? Which outlets perform best based on type, size, and location tier? What is the trend of sales growth across establishment years Which products have high visibility but low sales? What are the Top 10 products by sales and customer ratings? How does customer satisfaction vary across product categories and outlet types?

Key Insights : Fruits & Vegetables and Snack Foods generate the highest sales revenue. Supermarket Type 1 outlets contribute the most to total sales. Sales distribution between Regular and Low Fat products is balanced. Outlets with more years of operation tend to generate higher sales. Some products show high visibility but lower sales, indicating potential marketing opportunities. Customer satisfaction ratings remain consistent across product categories. Business Value

This dashboard enables businesses to: Identify top-performing product categories Evaluate outlet performance and operational efficiency Understand customer purchasing behavior Monitor sales growth trends Make data-driven strategic decisions

Project Conclusion : The Blinkit Sales Dashboard demonstrates how data visualization tools can convert raw business data into actionable insights. By using Microsoft Power BI, this project highlights the importance of data modeling, DAX calculations, and interactive visualization in modern business analytics. The dashboard helps decision-makers identify growth opportunities, optimize outlet strategies, and improve product performance through data-driven analysis.

Outlet Location – Tier classification of outlets (Tier 1, Tier 2, Tier 3)

This structure helps implement a Star Schema data model which improves performance and simplifies analysis.
