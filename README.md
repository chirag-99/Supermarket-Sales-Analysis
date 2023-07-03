# Supermarket-Sales-Analysis

The dataset contains sales details of different stores of a supermarket chain that has multiple stores in different parts of the US.
With columns including Ship Mode, Segment, Country, City, State, Postal code, Region, Category, Sub-category, Sales, Quantity, Discount, and Profit.

Dataset source: Kaggle(public).

This dataset was analyzed in 2 parts: Power BI and MongoDB.

## 1. Power BI

The dataset was cleaned and prepared for analysis, followed by the implementation of stacked bar charts, pie charts, co-relation sketches, map charts, and card implementation of key attributes connected to sales and profit. Later, a collective dashboard was developed based on all the generated reports highlighting the key factors leading to sales. For the same, filters were applied for selective display and slicers were defined where necessary.

Top conclusions from the dashboard:

1.1. 31.5% of the sales revenue is generated from west-America, particularly, California being the highest contributor. Followed by 29.5% of sales revenue being generated from East America wherein New York was the highest contributor. Discounts can be offered to customers of this region to increase sales and improve membership counts.

1.2. 59.2% of the customers prefer the standard shipping method, thus the cost of other shipping methods could be an issue of not being much popular. Also, this implies that if there are some customers who require urgent stuff they might prefer any other shopping store with lower prices and quicker shipping methods.

1.3. Maximum profit is earned on each technology product being sold, thus periodic sales could be arranged on technology products as the net margin in case of sale would also lead to profit.

1.4. Consumer segment has contributed the most to sales in terms of $1.16M revenue. Thus the prime focus of the store must be on these customers.

## 2. MongoDB

MongoDB was used to assemble and form the database out of the dataset. NoSQL queries were written to analyze the following objectives:

2.1. Orders per segment: This analysis highlighted the segments with the maximum orders.

2.2. Profit per state: This analysis highlighted the states of the US with the most profitable orders.

2.3. Sales with discount: This analysis highlighted the total sales when the discount was offered.

2.4. Sales without discount: This analysis highlighted the total sales when the discount was not offered.

##### After the analysis, it was found that total sales are more when discounts are offered on the orders as compared to when the discounts are not offered.

2.5. Big Sales: Since California was the most profitable state, this analysis highlighted the attributes of records wherein the total sales were > $5000.
