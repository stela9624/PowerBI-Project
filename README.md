
![image](https://github.com/user-attachments/assets/7465f244-b758-4840-b058-804aae91aa2d)

# PowerBI-Project
Power BI Sales Performance Dashboard Analysis
Project Name: BigBasket Sales Performance Analysis Dashboard

Introduction
BigBasket is India's leading online grocery delivery service that provides a wide range of grocery items to customers. The purpose of this project is to analyze the sales performance of BigBasket using Power BI and provide actionable insights based on key performance indicators (KPIs). The dashboard developed offers dynamic visualizations that enable business users to make data-driven decisions.
Data Source

File Type: Excel Spreadsheet

Number of Rows: 8,523

Columns: 12

Key Attributes:
Item Fat Content
Item Type
Outlet Establishment Year
Outlet Location Type
Outlet Size
Outlet Type
Item Visibility
Item Weight
Sales
Ratings

Business Requirements
The dashboard was built based on the following key business questions:
What is the total sales revenue?
What is the average sales per transaction?
What are the most and least sold product categories?
How do sales vary based on fat content, outlet location, and outlet size?
What is the impact of different outlet types on total sales?
What are the trends in outlet establishment and their sales performance?

Key Performance Indicators (KPIs)
The following KPIs were identified and implemented in the dashboard:
Total Sales: Overall revenue generated from all items sold.
Average Sales: Average revenue per transaction.
Number of Items Sold: Total number of unique items purchased.
Average Customer Rating: Average rating provided by customers for their purchases.

Data Cleaning and Transformation
Before visualization, data preparation was performed in Power Query with the following actions:
Standardized Values: Replaced inconsistent item fat content values (e.g., 'LF' to 'Low Fat', 'R' to 'Regular').
Handled Missing Data: Identified missing values in item weight and ratings.
Created Calculated Fields: Used DAX functions to compute new metrics such as total sales and average sales.
Formatted Data Types: Ensured numerical and categorical fields were correctly formatted.

Visualizations and Insights
The dashboard consists of multiple dynamic visualizations to enable deeper insights:

Sales Performance Overview:

Displays total sales, average sales, number of items sold, and average ratings in a KPI card format.

Sales by Fat Content:

Donut chart to analyze total sales, average sales, number of items, and ratings by fat content.

Outlet Sales Analysis:

Clustered bar chart showing fat content breakdown by outlet location.

Line chart depicting total sales by outlet establishment year.

Donut chart analyzing sales distribution by outlet size.

Funnel chart analyzing total sales by outlet location.

Item Type Performance:

Bar chart highlighting sales performance of different product categories.

Outlet Type Analysis:

Matrix visual displaying total sales, average sales, number of items sold, and average rating per outlet type.

Interactive Filters & User Experience Enhancements
To enhance user experience, the following interactive features were implemented:

Slicers for Filtering:

Outlet location, outlet size, and item type filters to dynamically adjust visualizations.

Clickable Charts:

Enabled cross-filtering between different charts to allow users to drill down into specific data points.

Results & Business Impact
The Power BI dashboard provided significant insights into BigBasket's sales trends and customer behavior. Key findings include:

Sales Distribution: Medium-sized outlets generated the highest revenue, followed by small outlets.

Top-Selling Categories: Fruits and vegetables had the highest sales volume, while household items had the highest average sales.

Regional Performance: Tier 3 cities contributed the most sales revenue compared to Tier 1 and Tier 2.

Customer Ratings: The average customer rating was 3.9, indicating room for service quality improvement.

Newly Established Outlets: Outlets established in 2018 performed the best in terms of revenue generation.

Conclusion & Future Scope
This Power BI dashboard effectively showcases BigBasket's sales performance across multiple dimensions. It enables decision-makers to:

Identify high-performing and low-performing outlets.

Optimize inventory distribution based on sales trends.

Improve customer experience by analyzing ratings and feedback.

Make data-driven decisions to enhance sales growth.

Future enhancements to this dashboard could include:

Integration with real-time data sources for live reporting.

Predictive analytics to forecast sales trends.

More granular customer segmentation analysis.

Prepared By: Stella Rani L
Date: 2/16/2025
