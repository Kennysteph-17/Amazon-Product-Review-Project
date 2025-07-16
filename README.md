# Amazon-Product-Review-Project
This project entails data cleaning, data transformation, and analyzing a dataset of product listings and their associated customer reviews from the Amazon e-commerce platform. Using Microsoft Excel Power Query and Microsoft excel, the data was restructured to support effective insights using Pivot Tables and Dashboard Visualization.
## Objectives
The analysis answers the following key business questions:

1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs. discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
9. What is the total potential revenue (actual_price × rating_count) by category?
10. What is the number of unique products per price range bucket (e.g., <$200, $200–$500, >$500)?
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.

## Results Summary
The complete analysis results with pivot table and chart visuals (Q1 to Q14) are available in the results.md file.

## Tools & Techniques Used
Power Query: Data transformation (split, clean, unpivot, zip, expand, join)
Excel Pivot Tables: Aggregations, distinct counts, averages, sums
Excel Pivot Charts: Column, Pie, Bar and Scatter plots
Calculated Columns: Used for bucket creation, combined scores and conditional flags

# Structured Query Language (SQL)
SQL was used in exploring Kultra Mega Store (KMS) in this project. SQL means structure Query language for accessing, managing and modifying data in a relational dtatabase.

SQL Tool was used to answer the following questions after I had successfully imported my data into a database i created which was Kultra Mega Store .

1. Retrieve the total sales for each product category.
2. Find the number of sales transactions in each region.
3. Find the highest-selling product by total sales value.
4. Calculate total revenue per product.
5. Calculate monthly sales totals for the current year.
6. Find the top 5 customers by total purchase amount.
7. Calculate the percentage of total sales contributed by each region.
8. Identify products with no sales in the last quarter.


select *from[dbo].[SalesData]


## Acknowledgements
Special thanks to:
Digital Skills Africa – for providing the upskilling opportunity and curriculum.
Incubator Hub – for guidance, mentorship, and technical support throughout the project.
Author
STEPHEN KEHINDE MOSES
Email: kennysteph2012@gmail.com
