# customer_spending_behavior
A project built using SQL

About

This project includes an exploratory analysis of customer spending behavior of a bike company's sales data in four countries; USA, France, Germany, and UK. The company sells three types of bike related products; bike accessories, bikes, and bike clothing. The main task of this project is to understand the buying/spending behavior of  customers based on the price of the products offered by the company. The original dataset was sourced from Kaggle. 

Data cleaning

Some of the attributes in the original dataset were not needed for the analysis. Therefore, a new table was created including only the details of necessary information. The raw dataset was mostly clean, except for the Null values in the country column which were deleted during the cleaning phase. 

Queries

To answer business questions related to customer spending behavior, sales trend, products revenue etc., SQL queries were written in BigQuery. Since there were multiple questions to address, queries related to them were combined into a single script using temporary tables. This approach makes it easier to save queries related to individual questions as CSV files for visualizations. 

Data visualization

All the CSV files generated from the queries were first uploaded to a single excel document of xlsx fomat. This was done to save time uploading individual files and to make it easier to establish relationships between individual sheets to apply filters afterwards on Tableau Public for visualizations.

Some of the key conclusions from this dataset are:

Female didn't bother about the price point and spent more and purchased higher units of bikes and bike accessories compared to men. Similarly in the age group, Adults, i.e., between the age of 30 and 45 spent more, and were the highest revenue contributors with more number of units of all categories in their pockets.  The overall purchasing behavior of customer irrespective of the age and gender is that they're purchasing more units of bike accessories because of its price point as they're the cheapest amongst other categories. 
