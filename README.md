## Product Sales Analysis
---

### Table of Contents
- [Overview](#Overview)
- [Data source](#Data-source)
- [Tools](#Tools)
- [Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)
- [Data Analysis](#Data-Analysis)
- [Findings](#Findings)
- [Recommendations](#Recommendations)

###  Overview 
An analysis of product sales over several months to determine the products that sold the most during the period, products that were often sold together, cities that recorded the highest sales, and the optimal time of day to display advertisements. 

###  Data Source
The dataset was obtained from this repo: https://github.com/KeithGalli/Pandas-Data-Science-Tasks

###  Tools
- Python
- Pandas
- Jupyter Notebooks

###  Data Cleaning and Preparation
- Creation of new columns: 'Sales Amount' column from 'quantity ordered' and 'price each' columns, 'City' and 'State' columns from 'Purchase Address' column, and date (mm/dd/yyyy) and time (HH:MM) columns from 'Order Date' column. 
- Type conversion: 'Quantity Ordered' and 'Price Each' columns to numeric, and Date and Time columns to datetime format.

### Data Analysis
1. Which month had the best sales? How much was earned that month?
2. Which city had the highest sales?
3. What time should the company display advertisements to maximize the likelihood of customers buying the products?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

### Findings
- Month and cities with best sales: December 2019 was the month with the highest sales of all the months with $4,613,443.34 in total sales. The worst month was January 2020 with $8,670.29 in total sales. San Francisco, CA had the highest amount of sales during the period with $8,262,203.91 in total sales, while Portland, ME had the least amount of sales at $449,758.27.

- Product that sold the most: The product that sold the most during the period was AAA Batteries (4-pack) with 31,017 in total quantities sold. A graph of quantity sold and price against product shows that products that sold the most were those with lower prices. Therefore, it is possible that one of the reasons why some products such as AAA Batteries (4-pack) and AA Batteries (2-pack) sold the most during the period was low prices as these products were priced lower than the other products. This could also be an indication of price sensitivity among the customers.

- Products commonly sold together: Some of the products that are commonly sold together as 4 items include: 'iPhone', 'Lightning Charging Cable', 'Apple Airpods Headphones' and 'Wired Headphones' (sold together 4 times during the period), and 'Google Phone', 'USB-C Charging Cable', 'Bose SoundSport Headphones' and 'Wired Headphones' (sold together 3 times during the period). Some of the products that are commonly sold together as 3 items include: 'Google Phone', 'USB-C Charging Cable' and 'Wired Headphones' (sold together 87 times during the period), 'iPhone', 'Lightning Charging Cable' and 'Wired Headphones' (sold together 62 times during the period), and 'iPhone', 'Lightning Charging Cable' and 'Apple Airpods Headphones' (sold together 47 times during the period) among other items which are commonly sold together as 3 items. Some of the products that are commonly sold together as 2 items include: 'iPhone' and 'Lightning Charging Cable' (sold together 1,005 times during the period), 'Google Phone' and 'USB-C Charging Cable' (sold together 987 times times during the period), and 'iPhone' and 'Wired Headphones' (sold together 447 times during the period) among other items which are commonly sold together as 2 items. 

- Optimal time for advertising: The optimal time for the company to display advertisements is around 19:01:00 as this time produced $54,503.14 in total sales during the period under consideration.


### Recommendations 
- Price Adjustments: The graph of quantity sold and price against product points to a possibility of price sensitivity among the customers. The business should therefore consider competitive pricing strategies to balance volume and profitability. For example, lowering the price of high-demand items slightly could result in higher sales volumes.

- Regional Marketing: Certain cities recorded higher sales than others. This could be due to market size, demand, or regional preferences. The business should tailor marketing strategies to regions or cities where sales are higher or invest more in advertising and promotions in high-performing cities to further capture the market. For cities with lower sales, the business should investigate whether lack of awareness, competition, or other factors are limiting sales. Consider market penetration strategies such as region-specific promotions or opening new retail channels in these areas.

- Product Bundling and Cross-Selling: Analysis of products sold together provides insights into natural bundles of products frequently purchased in combination. The business should create product bundles based on frequently bought-together products such as 'Google Phone', 'USB-C Charging Cable' and 'Wired Headphones', or 'iPhone' and 'Lightning Charging Cable'. Additionally, the business should consider suggesting related or complementary products at the point of sale or in online shopping carts to increase the average order value.

- Time-Based Advertising: An analysis of the time of day with the highest sales, identifies peak hours when customers are more likely to make purchases. In this case, the time was around 19:01:00. The business should increase advertising efforts or send marketing emails during this time to maximize the likelihood of conversion. This can be done with pay-per-click (PPC) ads, social media campaigns, or targeted email marketing campaigns during these high-conversion hours. Additionally, the business should consider offering special discounts or flash sales during these peak times to further encourage purchases.


