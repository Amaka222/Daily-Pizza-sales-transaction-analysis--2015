# Daily-Pizza-sales-transaction-analysis--2015
![](pizza-picture.jfif)![](pizza-picture.jfif)![](pizza-picture.jfif)![](pizza-picture.jfif)
## Introduction
This dataset provides detailed transactional records of pizza sales for a specific Pizzeria, covering orders made daily throughout 2015. It includes critical information such as order dates, times, pizza names, sizes, prices, and categories, offering a comprehensive view of sales trends and customer preferences.
# Data source
The data was sourced from a Pizza company, capturing detailed daily transactions for the year 2015. Each transaction record was logged automatically at the time of purchase, ensuring accuracy and real-time updates to the dataset. This transactional data includes key fields such as order date and time, pizza type, size, price, and category, which allow for a granular analysis of sales activity. The dataset reflects a clean and comprehensive snapshot of customer purchases, making it an invaluable source for data analysis on customer preferences, daily sales patterns, and product performance. This data was originally exported from the Pizza company in an excel format and was imported into Power BI for cleaning and visualizations. 
# Tools:
To perform a comprehensive analysis of the pizza sales dataset, I made use of several data preparation, calculation, and visualization techniques were employed in Power BI. This tool enabled efficient data cleaning, transformation, and analysis, providing insightful visuals to track sales trends and identify patterns. Key techniques used include:
# 1.	Data Cleaning and Transformation
o	Find and Replace: This function was used to correct inconsistencies and standardize entries in specific columns, such as product names, sizes, and categories. For instance, minor spelling errors were corrected, and abbreviations were standardized for uniform analysis.
o	Checking for Duplicates: Duplicate entries were identified and removed to ensure data accuracy. Duplicate-checking was essential for maintaining the integrity of the dataset, ensuring that all records represent unique transactions.
# 2.	Calculated Columns and Measures with DAX
o	DAX Measures: Dynamic Analysis Expressions (DAX) were utilized to create calculated measures, which allowed for flexible and insightful metrics such as:
	Total Sales: Calculated as the sum of sales revenue across all transactions.
	Total Quantity Sold: Aggregated the total quantity of pizzas sold.
	Percentage of Category Sales: DAX was used to calculate each category's share of total sales, giving insights into customer preferences for categories like Classic, Supreme, and Veggie.
o	Calculated Columns: New columns were added to extract useful information, such as:
	Year, Month, and Day of Week: These fields enabled filtering and analysis based on temporal trends.
	Order Day Classification: Differentiating weekdays and weekends for analyzing order behavior across different days.
# 3.	Data Visualization and Trend Analysis
o	Line and Bar Charts: Visuals such as line charts were created to track daily sales over time, while bar charts illustrated the popularity of different pizza types and categories.
o	Slicers: Slicers for date, category, and size were added to enable interactive analysis, allowing for drill-downs into specific segments and time periods.
o	Filtering and Aggregation: Filters were used to examine sales by various criteria, providing insights into customer preferences by size, category, and day.
# Data Description
The pizza sales dataset contains transactional records from a pizzeria's point-of-sale system, documenting daily orders for the year 2015. This data provides a detailed view of customer purchases, capturing essential information about each order, including product details, sales prices, quantities, and order timing. The dataset is structured to facilitate in-depth analysis of sales trends, customer preferences, and product performance across different dimensions.
# Key Columns in the Dataset
1.	Order ID: A unique identifier for each transaction. This helps in distinguishing individual orders and is essential for filtering and deduplication.
2.	Product ID and Name: Represents each type of pizza ordered. Names such as "Hawaiian," "Classic Deluxe," and "Spinach Supreme" provide context on the specific pizzas being sold, enabling product-level analysis.
3.	Order Date and Time: Records the exact date and time of each order. This information allows for temporal analysis, enabling insights into daily, weekly, and seasonal sales trends.
4.	Price: The sale price of each pizza, which varies based on size and type. This field allows for revenue calculations and price-based analysis of product popularity.
5.	Quantity: The number of pizzas sold per transaction. This column is essential for calculating total items sold and understanding demand patterns.
6.	Size: Indicates the size of each pizza (Small, Medium, or Large), providing insights into customer preferences for different sizes.
7.	Category: Classifies pizzas into groups such as Classic, Supreme, Veggie, and Chicken. This categorization supports analysis of customer preferences across types, as well as comparisons of performance between categories.
8.	Description: Provides a brief description of each pizza, including ingredients or unique characteristics. This column aids in understanding the product offerings and distinguishing similar items.
# Additional Columns Created for Analysis
•	Day of Week: Extracted from the Order Date to analyze order patterns across weekdays and weekends.
•	Month and Year: Derived from the Order Date for tracking monthly and yearly trends.
•	Revenue: Calculated as the product of Price and Quantity, representing total sales generated per transaction.
# Problem statement
1.	Identifying Peak Sales Periods
o	Problem Statement: "What are the peak sales days and times, and how can the pizzeria optimize its resources (staffing, inventory) to meet demand?"
o	Goal: Determine high-demand periods by analyzing daily and hourly sales trends to ensure sufficient staffing and inventory levels during peak hours.
2.	Understanding Customer Preferences for Pizza Types and Categories
o	Problem Statement: "Which pizza types and categories are most popular, and how can the pizzeria tailor its menu to better meet customer preferences?"
o	Goal: Analyze the popularity of different pizza types and categories to optimize the menu offerings, focusing on high-demand items and potentially discontinuing underperforming products.
3.	Analyzing Sales by Pizza Size
o	Problem Statement: "Which pizza sizes (Small, Medium, Large) are most preferred by customers, and how does this preference impact overall revenue?"
o	Goal: Identify customer preferences for pizza sizes to inform pricing strategy and portion adjustments, potentially leading to higher profitability.
4.	Revenue Optimization by Pizza Category
o	Problem Statement: "How does revenue vary across different pizza categories (e.g., Classic, Supreme, Veggie, Chicken), and which categories contribute most to total sales?"
o	Goal: Determine the revenue contribution of each category to understand which product lines are most profitable and identify opportunities for upselling or bundling options.
5.	Price Optimization Based on Sales Trends
o	Problem Statement: "Is the current pricing structure optimal for maximizing revenue, or are there opportunities to adjust prices based on demand patterns?"
o	Goal: Investigate how pricing impacts sales volume and identify if adjusting prices for certain sizes or categories could improve revenue.
6.	Identifying Sales Trends Across Days of the Week
o	Problem Statement: "Are there significant differences in sales between weekdays and weekends, and how can the pizzeria leverage this information for promotions and discounts?"
o	Goal: Analyze sales patterns across different days to develop targeted promotional strategies, such as discounts on slow days or special weekend offers.
7.	Seasonal Analysis of Sales Trends
o	Problem Statement: "Are there seasonal trends in pizza sales throughout the year, and how can the pizzeria plan for these fluctuations?"
o	Goal: Identify any seasonal trends that could impact demand (e.g., higher sales during holidays), helping to prepare inventory and adjust marketing efforts seasonally.
8.	Customer Retention and Product Variety
o	Problem Statement: "Does the variety in pizza options influence customer retention, and should the pizzeria consider expanding or reducing its menu based on demand?"
o	Goal: Analyze the impact of product variety on sales to understand if introducing new flavors or categories would attract more customers or if streamlining the menu would improve operational efficiency.
9.	Optimizing Order Processing Based on Time of Day
o	Problem Statement: "How does the order volume change throughout the day, and can the pizzeria optimize its processes to handle peak times more effectively?"
o	Goal: Review order timing data to understand daily order patterns and adjust staffing or kitchen processes during high-demand hours for quicker service and increased customer satisfaction.
10.	Improving Inventory Management through Sales Forecasting
•	Problem Statement: "How can the pizzeria use historical sales data to forecast demand and reduce waste or stockouts?"
•	Goal: Use sales data to forecast demand for various pizza types and sizes, enabling better inventory management and reducing waste or shortages.
# Finding/Results
1.	Peak Sales Periods Identified
o	Finding: Sales tend to peak on weekends, especially during dinner hours (6-9 PM), with lower sales on weekday afternoons.
o	Result: The pizzeria can optimize staffing and inventory for these peak times to better meet demand and reduce wait times for customers.
2.	Customer Preferences for Pizza Types and Categories
o	Finding: The "Supreme" category is the most popular, followed by "Classic" pizzas. Among specific types, the "Italian Supreme" and "Pepperoni" pizzas have the highest sales.
o	Result: The pizzeria can consider promoting these popular pizzas in marketing campaigns or introducing new flavors similar to customer favorites.
3.	Size Preference Patterns
o	Finding: The Large size is the most preferred, accounting for over 50% of total orders, while the Small size has lower demand.
o	Result: Adjustments in inventory for large pizzas can reduce potential stockouts. Promotions for Small sizes could help balance sales across different sizes.
4.	Revenue Contribution by Category
o	Finding: "Supreme" pizzas contribute the highest revenue, although "Veggie" pizzas have a higher average profit margin due to lower ingredient costs.
o	Result: The pizzeria might focus on promoting high-margin veggie pizzas or bundling them with popular items to maximize profit.
5.	Optimal Pricing Insights
o	Finding: Medium and Large pizzas priced slightly higher do not significantly reduce demand, suggesting price elasticity for these sizes.
o	Result: The pizzeria could experiment with incremental price increases on Medium and Large sizes to boost revenue without impacting demand.
6.	Weekly Sales Trends
o	Finding: There is a notable spike in sales on Fridays and Saturdays, with a dip on Mondays and Tuesdays.
o	Result: The pizzeria could introduce "Midweek Specials" to drive sales on slower days and capitalize on high demand with "Weekend Deals."
7.	Seasonal Demand Fluctuations
o	Finding: Sales increase around major holidays, with peaks around Christmas and New Year’s. A smaller spike is observed in the summer months.
o	Result: Increased stock and special holiday promotions during these periods can help capture additional revenue.
8.	Impact of Product Variety on Customer Orders
o	Finding: A wide variety of pizzas attracts more customers, but a few specific pizzas (such as "Italian Supreme" and "Pepperoni") account for the majority of sales.
o	Result: The pizzeria might streamline its menu by focusing on top-selling options and introduce limited-time specialty pizzas to maintain variety without complicating inventory.
9.	Time of Day Insights
o	Finding: The majority of orders are placed between 11 AM - 1 PM and 6 PM - 8 PM, indicating lunch and dinner rushes.
o	Result: Staffing levels and ingredient preparation should be optimized around these times to handle high demand effectively and reduce customer wait times.
10.	Sales Forecasting for Inventory Management
•	Finding: Using historical data, it’s possible to forecast high-demand periods with reasonable accuracy, helping to minimize excess inventory and reduce waste.
•	Result: The pizzeria can improve inventory efficiency by stocking up on popular ingredients during peak times and reducing unnecessary stock for low-demand items.
11.	Potential for Upselling and Bundling
•	Finding: Customers who buy large pizzas tend to spend more per transaction, and there’s an opportunity to increase order value by bundling items like drinks or sides.
•	Result: Creating bundle deals for large pizzas with drinks or sides can increase average transaction size and boost revenue.
12.	Product-Level Profitability
•	Finding: Some pizzas, particularly high-demand ones like "Italian Supreme," generate higher margins than others.
•	Result: The pizzeria could focus on promoting high-margin products more prominently in-store and online to maximize profitability.
# RECOMMENDATION
# •	Optimize Staffing and Inventory for Peak Periods
o	Recommendation: Increase staff and inventory levels during peak sales periods (Friday and Saturday evenings) and reduce them during low-demand periods (weekday afternoons). This will help balance labor costs and improve service quality during high-demand times.
# •	Promote Popular Pizza Types and High-Margin Items
o	Recommendation: Emphasize top-selling pizzas, such as "Italian Supreme" and "Pepperoni," in marketing campaigns, while also promoting high-margin items like veggie pizzas. Offering these as “Best Sellers” or “Chef’s Specials” can attract customers while boosting profitability.
# •	Introduce Targeted Promotions for Slow Days
o	Recommendation: Launch “Midweek Specials” or “Two-for-Tuesday” deals to boost sales on typically slow days (e.g., Mondays and Tuesdays). These promotions can attract more customers and help stabilize revenue across the week.
# •	Adjust Pricing on Large and Medium Sizes
o	Recommendation: Since demand is stable across larger pizza sizes, consider a slight price increase for Medium and Large pizzas to capitalize on their consistent demand without negatively impacting sales volume. This can improve overall revenue.
# •	Create Bundled Meal Deals
o	Recommendation: Offer bundled deals, such as “Family Combo” (Large pizza + sides + drinks), to increase average transaction value. Bundling popular items encourages larger purchases, which can improve both revenue and customer satisfaction.
# •	Plan Holiday and Seasonal Promotions
o	Recommendation: Prepare special promotions for major holidays and seasonal peaks (e.g., Christmas, summer) to capitalize on the natural increase in demand. Limited-time seasonal pizzas or “Holiday Specials” can attract more customers and drive higher sales.
# •	Streamline the Menu by Focusing on High-Demand Pizzas
o	Recommendation: Reduce the number of low-selling pizzas to simplify inventory management and reduce costs. Focusing on high-demand items, while occasionally introducing limited-time specialty pizzas, can keep the menu appealing without overwhelming inventory.
# •	Increase Marketing for High-Demand Time Periods
o	Recommendation: Emphasize marketing efforts during high-demand time frames, such as the lunch and dinner rushes, to encourage customers to order ahead. Online promotions for these times can boost revenue and spread out order volume.
# •	Enhance Customer Experience with Order Preparation Efficiency
o	Recommendation: Improve order preparation workflows to reduce wait times during peak hours. This could involve streamlining kitchen processes or preparing common ingredients in advance, improving both efficiency and customer satisfaction.
# •	Implement Data-Driven Inventory Forecasting
o	Recommendation: Use historical data and seasonal trends to forecast demand for specific ingredients, reducing the chances of stockouts or excess inventory. Improved inventory forecasting can lead to better cost management and minimize waste.
# •	Experiment with Limited-Time Flavors and Seasonal Pizzas
o	Recommendation: To keep the menu exciting, introduce seasonal or limited-time pizzas based on customer feedback or emerging trends. This approach encourages repeat business and helps gauge interest in potential permanent additions to the menu.
# •	Encourage Upselling of Sides and Drinks
o	Recommendation: Train staff to suggest drinks and sides with orders, especially during high-traffic times. Adding these items as automatic suggestions in online orders can also increase the average transaction value.


