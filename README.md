# Coffee Sales Project

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source and Overview](#data-source-and-overview)
- [Tools](#tools)
- [Data cleaning, Data integration and Data analysis](#data-cleaning-data-integration-and-data-analysis)
- [Insights](#insights)
- [Recommendations](#recommendations)

### Project Overview
---
y0na Limited, a company specializing in sales of confectioneries and coffee provided a dataset for analysis to gain insights into their coffee sales performance, customer behaviour, and product profitability. The dataset provided included multiple sheets that captured various aspects of the business, including orders, customers, products, total sales, and geographic distribution. The objective of this project is to analyze the data to uncover patterns, diagnose potential issues, and make predictions for future business strategies.

### Data Source and Overview
---
The dataset is an Excel file that contains the following sheets:
1.	Orders
2.	Customers
3.	Products

I'll now examine the content of each sheet to understand the data structure and formulate the documentation report. 

1.	Orders Sheet: This sheet captures individual orders, including customer details, products purchased, and sales values. The Columns include Order ID, Order Date, Customer ID, Product ID, Quantity, Customer Name, Email, Country, Coffee Type, Roast Type, Size, Unit Price, Sales, Coffee type name, Roast type name, Loyalty Card.

2.	Customers Sheet: This sheet contains customer demographic data, which is crucial for understanding purchasing behaviour and segmentation. The Columns include: Customer ID, Customer Name, Email, Phone, Street Address, City, Country, Postcode, Loyalty Card

3.	Product Sheet: This sheet details the coffee products offered by Yona, including pricing and profitability, which will help assess product performance. The Columns include Product ID, Coffee Type, Roast Type, Size, Unit Price, Price per 100g, and Profit.

### Tools
---
- Excel (EDA. Data Cleaning, Data Analysis)
  - [Download here](https://1drv.ms/x/c/fd5c593e64fd8650/Efyu6hY-8zJAmH6X2PZx73YBfXjSzDaKA7bLoueFt6WTUg)
- Power BI (Creating a report) [Download here](


### Data Cleaning, Data Integration and Data analysis
1.	Data Cleaning:
- I Checked for missing values and inconsistencies in the data, especially in the Orders and Customer sheets.
- I Verified that all numerical data (e.g., sales, quantities, profits) were correctly formatted for analysis.

2.	Data Integration:
-	I used the Vlookup, Index match and Xlookup functions to merge relevant data across different sheets using common keys (e.g., Customer ID, Product ID) to create a comprehensive dataset for analysis.

![OrdertableBI](https://github.com/user-attachments/assets/e1002c12-e5f6-4843-9aa7-27324bdb9894)
  
3.	Data Analysis:
- I Performed summary statistics on sales data to identify top-performing products and customers.
- I analyzed sales trends over time by creating a pivot table called "Total Sales" 
- I	Compared sales performance across different countries and identified potential causes for underperformance in certain regions.
- I analyzed the impact of loyalty cards on customer purchasing patterns.
- I used historical sales data to forecast future sales trends and identify potential growth areas.
- I assessed the likelihood of repeat purchases based on customer demographics and previous order behaviour.

### Exploratory Data analysis
---
EDA involved answering the following questions:
- Sales Analysis: What are the trends in coffee sales over time, and which products are contributing the most to revenue?
- Customer Behavior: Who are the top customers, and what are their purchasing habits?
- Geographical Performance: Which countries generate the most sales, and how does sales performance vary across regions?
- Product Profitability: Which coffee products have the highest profit margins, and how does pricing affect sales?
- Customer Loyalty: How does the presence of a loyalty card influence customer purchases?

![Loyaltycard](https://github.com/user-attachments/assets/8d533006-3dda-4fae-b05f-08b4ccb044c1)


### Insights
---
1.	Descriptive insights:
-	The United States is the largest market for y0na Limited, generating the highest sales revenue.
-	Excelsa coffee is the most popular product, followed closely by Arabica.

![USA](https://github.com/user-attachments/assets/ec4d5e42-9d46-4c82-8931-c4f588fe3800)

![Arabica](https://github.com/user-attachments/assets/f6824f57-d773-4dff-b816-949782734b6f)


2.	Diagnostic Insights:
- Sales performance in the United Kingdom is significantly lower than in the United States and Ireland, possibly due to less effective marketing or distribution challenges.
- Customers with loyalty cards tend to purchase larger quantities and have a higher lifetime value.
 
3.	Predictive Insights:
- Sales are expected to peak during the holiday season, especially in November and December.
  
### Recommendations
---
- Introduce new product lines or promotions in the United Kingdom to help boost sales in that region.
- Focus on promoting "Robusta" Coffee type as it has the lowest sales.
- Pay more attention during the holiday period as that is the period where sales are high.



