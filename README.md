# predictive-modelling

# Executive Summary
This project is conducted on the dataset taken from an ongoing data challenge on Analyticsvidhya.com and it consists of transactional data of purchases made at a retail store. Our objective is to predict the discounted price of the product purchased, based on customer demographics. Additionally, we also performed market basket analysis on the data. Any other observation, unrelated to the prediction goal, is also recorded and summarized in the paper. 

# Problem Statement
A retail company “Walkart” wants to understand the customer purchase behavior (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month. The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product_category) and total purchase_amount from last month. Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

# Toolused : SAS JMP

# Data Specs
As the first step of data exploration, we calculated the summary level statistics of user and product related variables.
Number of distinct users: 5891
Number of distinct products: 3631
Number of different product categories: 20 (1 to 20)
Number of occupation categories: 21 (0 to 20)
Number of age bins: 7 (‘0-17’, ‘18-25’, ‘26-35’, ‘36-45’, ‘46-50’, ‘51-55’ and ‘55+’)
Number of city categories: 3 (‘A’, ‘B’ and ‘C’)
Number of categories in Stay in Current City Years: 5 (‘0’, ‘1’, ‘2’, ‘3’, ‘4+’)

# Methodology: Linear Regression
