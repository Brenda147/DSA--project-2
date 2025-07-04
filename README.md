# DSA--project-2

### Project Topic: Sales and Customer Performance Analysis for Kultra Mega Stores (KMS)

### Project Overview
To provide insights into product sales, customer segmentation, and operational costs in order to support data-driven decision-making for the Abuja division of KMS.

### Data Source
The primary source of data usesd here is Kultra Mega Stores Inventory that can be freely downloaded from an open source such as Kaggle or FRED or any other data repository site

### Tools used
1.	SQL Server
	•	Used to query and analyze sales, customer, and shipping data stored in relational database tables.
	•	SQL queries were written to extract insights related to product performance, customer segments, and shipping methods.

## Analysis
https://github.com/Brenda147/DSA--project-2/blob/main/KMS%20SQL%20CASE%20STUDY.sql

### Key Findings:
	•	Technology was the highest-grossing product category, contributing ₦5.98M in revenue.
	•	Western Nigeria outperformed other regions, while Northern remote regions underperformed.
	•	No sales of Appliances were recorded in Ontario – a missed opportunity for diversification.
	•	Delivery Truck was the most expensive shipping mode, potentially misaligned with order priorities.
	•	Bottom 10 customers showed low engagement, requiring personalized reactivation strategies.

### Case Scenario I
	1.	The product category with the highest sales was Technology, generating a total of ₦5,984,248.18 in revenue.
	2.	The top three regions in terms of sales were West, Ontario, and Prairie, while the bottom three regions were Yukon, Northwest Territories, and Nunavut.
	3.	There were no recorded sales of appliances in Ontario, resulting in a total of ₦0 for that category in the province.
	4.	To increase revenue from the bottom 10 customers, it is recommended that KMS implements targeted marketing campaigns to re-engage these customers. Management should also consider offering personalized discounts or loyalty programs, conducting customer surveys to better understand their needs, and utilizing email automation to follow up with tailored product suggestions and exclusive deals.
	5.	KMS incurred the highest shipping cost using the Delivery Truck method, with a total expenditure of ₦51,971.94.

## Case Scenario II
	6.	The most valuable customers were those with the highest total sales, primarily purchasing products in categories such as Technology, Furniture, and Office Supplies.
	7.	The small business customer with the highest sales was identified through a query that filtered for the ‘Small Business’ segment and aggregated sales. (Exact name to be retrieved from the database.)
	8.	The corporate customer who placed the most orders between 2009 and 2012 was determined by grouping orders by customer within the ‘Corporate’ segment and counting order IDs. (Exact name to be retrieved from the database.)
	9.	The most profitable consumer customer was identified by grouping customers in the ‘Consumer’ segment and summing their total profit. (Customer name to be confirmed from the dataset.)
	10.	The customer(s) who returned items were identified using a return flag in the dataset, along with their respective segment classification. (Details to be confirmed by return-related query.)
	11.	While the Delivery Truck was the most economical shipping method, it also incurred the highest cost, suggesting it was used frequently—even potentially for high-priority orders. If low-priority orders were being shipped using Express Air, which is the fastest and most expensive method, or if high-priority orders were delayed due to use of Delivery Truck, this indicates an inefficient use of shipping resources. A detailed breakdown of shipping mode by Order Priority is required to fully confirm whether KMS’s shipping cost allocation was appropriate.

### Recommendations:
	1.	Re-engage Bottom Customers through loyalty programs and personalized offers.
	2.	Audit Shipping Costs and realign shipping modes with order priorities to reduce inefficiencies.
	3.	Explore Appliance Market in Ontario with promotional campaigns and product education.
	4.	Invest in High-Performing Segments such as Technology and Corporate customers.
	5.	Track Returns and Complaints to improve product quality and customer satisfaction.

 


