This project focuses on analyzing Amazon product sales data to uncover key insights and trends using Power BI. By leveraging sales data that includes product categories, actual prices, discounted prices, customer ratings, and more, this project delivers a comprehensive view of product performance.

Project Objective:

The primary goal of this project is to identify key sales trends, understand pricing strategies through discount analysis, and highlight customer preferences based on ratings. This will provide valuable insights for data-driven decision-making in e-commerce strategies.

![image](https://github.com/user-attachments/assets/56314386-f489-45a5-b178-eaf0bf7edf2f)

---

Key Insights:

1. Top 5 Revenue Generating Products:
Using Power BI's DAX (Data Analysis Expressions), I calculated total sales revenue for each product by multiplying the actual price with the quantity sold. The data was then visualized using a pie chart to showcase the top 5 products contributing the most to overall revenue.


2. Top 5 Highly Rated Products:
I aggregated product ratings using Power BI’s grouping and filtering options. A bar chart was used to present the top 5 products with the highest average ratings, providing a clear view of customer satisfaction trends.


3. Actual Price vs Discounted Price Analysis:
To compare the actual prices of products with their discounted prices, I created a bar chart that shows both values side by side. This was achieved using calculated columns in Power BI to derive average actual prices and discounted prices, enabling a clear comparison of price differences across various products.


4. Average Discount Percentage by Category:
I calculated the discount percentage for each product using a custom DAX formula:
Discount Percentage = (Actual Price - Discounted Price) / Actual Price * 100.
This allowed me to categorize products based on their discount percentages and visualize the average discount offered in each product category using a column chart.


5. Data Cleaning and Transformation:
Before analysis, the dataset had to be cleaned. Using Power BI’s Power Query Editor, I:

Handled missing data by filling blanks or replacing them with appropriate values.

Formatted date fields and standardized numerical data (e.g., prices and discount values).

Removed duplicate entries and outliers that could skew the analysis.



6. Creating Relationships and Data Modeling:
I imported multiple datasets (products, sales, and ratings) and created relationships between the tables using product IDs and category fields. This allowed me to perform cross-table analysis, which was crucial for developing comprehensive insights.


7. Interactive Dashboard:
I designed an interactive dashboard in Power BI to provide real-time insights. This dashboard includes filtering options that allow users to:

Drill down by product categories, time periods, and regions.

Explore data interactively by clicking on different visualizations to filter data dynamically.

View both summarized trends and detailed data points simultaneously.

Tools and Techniques Used:

Power BI: Used for data modeling, creating relationships between different datasets, performing calculations with DAX, and designing interactive dashboards.

Power Query Editor: For data transformation tasks such as cleaning data, formatting fields, and eliminating inconsistencies.

DAX (Data Analysis Expressions): Used to create calculated fields and measures, such as total revenue, discount percentage, and average ratings.

Excel: For the initial review and basic transformation of the dataset before importing into Power BI.

Visualizations:

Pie Chart: To display revenue distribution across top-performing products.

Bar Charts: To show comparisons, such as product ratings and price differences.

Column Charts: To illustrate discount percentages across categories.




---

Key Features of the Dashboard:

1. Revenue Insights: A detailed breakdown of sales and revenue by product, highlighting the top performers.


2. Customer Preferences: Rating-based analysis to understand which products are favored by customers.


3. Pricing and Discount Strategy: A clear view of how discounts vary across different categories and how they impact actual vs. discounted prices.


4. Interactive Filtering: The dashboard allows users to interactively filter data by product categories, time period, and discount ranges.




---

Challenges and Solutions:

Handling Missing Data: Some product entries had missing ratings or sales data. I used Power BI’s built-in data cleaning features in Power Query to fill or replace these values.

Data Integration: Integrating multiple datasets with different formats required setting up relationships and ensuring data consistency across tables.

Performance Optimization: As the dataset grew, I optimized the data model by removing unnecessary columns and creating aggregated tables to improve the performance of the dashboard.



---

This project demonstrates the potential of using Power BI for comprehensive sales data analysis. The interactive dashboard provides a holistic view of Amazon’s product performance, helping stakeholders make informed decisions regarding product pricing, discount strategies, and customer satisfaction.
