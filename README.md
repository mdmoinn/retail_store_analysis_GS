# Retail_store_analysis_GS

# Analyze and keep track of Key Performance Indicator's (KPI's) of Retail store

## Project Overview
Fair understanding of sales by- products, category, location and identify key areas to improve.
Aim to create a reporting system which will be monitored regularly and any drop in sales or abnormal behaviour would be noticed as soon as possible.


## Data Sources
Sales_data: The primary dataset used for this analysis is the "Sales_data.xlsx", containing detailed information about each sale made by the company.


## Tools
- Googlesheets:
	- Data cleaning
	- Data analysis
	- Graphical representation


## Data Cleaning preparation
In the initial data preparation stage, follwoing task were performed:
	- Data loading and inspection
	- Handling duplicate values
	- Data cleaning & formatting


### Exploratory Data Analysis
EDA invloved exploring the sales data to answer key questions, such as:
  - Customers with top transactions
  - Product sales for a period of 8th to 15th December
  - ARPU (Average revenue per user) for city and state
    - ARPU for state = Total revenue by the state/ Total number of customers in the state
  - Sales by category with city level breakup


### Data Analysis
Intresting formulas worked with:
	- SUMIF, SUMIFS, VLOOKUP, COUNTIF


### Results/Findings:
The analysis results are summarised as follows:
  - The top 3 customers are customer_id 712345388, 712345122 & 712345299
  - Maximum product sale was found to be 5372 for product_id 10000345 during 8th - 15th Dec
  - Maximum ARPU was observed in Uttar Pradesh with the value of 3234.17 & minimum in Maharashtra - 2024.14
  - Cereals in Bangalore region observed with highest sales of 9032 and lowest sales was found in Mysore - 1564


### Recommendations:
Based on analysis, following recommendations can be utilized:
  - Customers with low sales can be focused and provide them gift vouchers to increase the sale
  - During festive season its clearly seen that Cheese_200g is consumed very less, hence procuring of this item to be reduced during this season
  - Focus on expanding & promoting products in Mahrashtra region as ARPU is low in this region
  - Dairy products expansion can be done in Mysore, Kolkata, Chennai, Hyderabad & Lucknow. Cereals products expansion can be done in Mysore & Lucknow, Drinks & Bevrages expansion can be done in Lucknow, Pune, Mysore, Kolkata & Kanpur
