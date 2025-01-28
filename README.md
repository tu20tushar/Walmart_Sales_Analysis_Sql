# Walmart_Sales_Analysis_Sql
This project aims to explore Walmart sales data to identify top-performing branches and products, analyze sales trends of various products, and understand customer behavior. The goal is to study how sales strategies can be improved and optimized. The dataset was obtained from the Kaggle Walmart Recruiting - Store Sales Forecasting https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting
# Objectives of the Project
The major aim of this project is to gain insights into Walmart's sales data to understand the various factors that influence the sales performance of different branches.
# Dataset
This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows:

Column	Description	Data Type
invoice_id	Invoice of the sales made	VARCHAR(30)
branch	Branch at which sales were made	VARCHAR(5)
city	The location of the branch	VARCHAR(30)
customer_type	The type of the customer	VARCHAR(30)
gender	Gender of the customer making purchase	VARCHAR(10)
product_line	Product line of the product solf	VARCHAR(100)
unit_price	The price of each product	DECIMAL(10, 2)
quantity	The amount of the product sold	INT
VAT	The amount of tax on the purchase	FLOAT(6, 4)
total	The total cost of the purchase	DECIMAL(10, 2)
date	The date on which the purchase was made	DATE
time	The time at which the purchase was made	TIMESTAMP
payment_method	The total amount paid	DECIMAL(10, 2)
cogs	Cost Of Goods sold	DECIMAL(10, 2)
gross_margin_percentage	Gross margin percentage	FLOAT(11, 9)
gross_income	Gross Income	DECIMAL(10, 2)
rating	Rating	FLOAT(2, 1)

# Business Questions To Answer
# Generic Question
How many unique cities does the data have?
In which city is each branch?
# Product
How many unique product lines does the data have?
What is the most common payment method?
What is the most selling product line?
What is the total revenue by month?
What month had the largest COGS?
What product line had the largest revenue?
What is the city with the largest revenue?
What product line had the largest VAT?
Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
Which branch sold more products than average product sold?
What is the most common product line by gender?
What is the average rating of each product line?
# Sales
Number of sales made in each time of the day per weekday
Which of the customer types brings the most revenue?
Which city has the largest tax percent/ VAT (Value Added Tax)?
Which customer type pays the most in VAT?
# Customer
How many unique customer types does the data have?
How many unique payment methods does the data have?
What is the most common customer type?
Which customer type buys the most?
What is the gender of most of the customers?
What is the gender distribution per branch?
Which time of the day do customers give most ratings?
Which time of the day do customers give most ratings per branch?
Which day fo the week has the best avg ratings?
Which day of the week has the best average ratings per branch?















