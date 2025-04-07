# Walmart Sales Analysis Project

This project explores Walmart sales data to identify trends, uncover seasonal patterns, and understand the impacts of various factors such as holidays, fuel prices, and local economic conditions on weekly sales.

## Dataset Description
The dataset includes the following features:

1. Store: The ID of the store (e.g., Store 1, Store 2).
2. Date: The date of the transaction (YYYY-MM-DD format).
3. Weekly_Sales: The sales amount for a specific store and week.
4. Holiday_Flag: Indicator of whether the week contains a holiday (1: Holiday, 0: Non-Holiday).
5. Temperature: The average temperature during the week in the area of the store.
6. Fuel_Price: The price of fuel in the region where the store is located.
7. CPI (Consumer Price Index): A measure of inflation in the area.
8. Unemployment: The unemployment rate in the region.

## Dataset Source:
https://www.kaggle.com/datasets/mikhail1681/walmart-sales

## Tools Used
Google Colab: For writing and executing Python code.
Python Libraries:
  pandas: For data manipulation and exploration.
  matplotlib and seaborn: For visualizing trends and relationships.
  numpy: For performing numerical calculations.
  scipy: For statistical tests and analysis.
  
## Conclusions
1. Seasonal Sales Patterns: There is a significant sales peak during November and December, corresponding to the holiday shopping season, with a noticeable post-holiday drop in January.
2. Holiday Impact: Weekly sales are appreciably higher during holiday weeks compared to non-holiday weeks, reflecting the importance of holiday campaigns.
3. Economic Effects: Contrary to expectations, higher unemployment rates correlate with increased weekly sales, potentially indicating Walmart's appeal during economic downturns.
4. Fuel Prices and Inflation: Weekly sales correlate positively with CPI and fuel prices, suggesting that Walmart remains a preferred choice for cost-conscious shoppers during inflationary periods.
5. Top-Performing Stores: Certain stores consistently outperform others, likely influenced by local demographics and store-specific factors.

## Recommendations for Improvements
1. Incorporate external data such as regional demographics to provide deeper insights into store-specific performance.
2. Enhance inventory and staffing strategies by leveraging monthly and seasonal patterns.
3. Develop targeted holiday marketing campaigns based on historical sales data.
4. Explore interactive dashboards for real-time analysis and visualization.
