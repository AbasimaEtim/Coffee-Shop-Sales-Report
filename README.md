# Coffee Shop Sales Report

## Introduction:
This documentation analyzes a coffee shop dataset focusing on coffee and tea sales performance over the past three months (April-June 2023). Since understanding product performance and sales trends is important for informed decision-making within any industry, this analysis aims to uncover valuable insights to help the coffee shop optimize its product offerings, pricing, and marketing efforts. 

#### Tool Used: Power BI


## The Dataset: 
The Dataset was shared from: 
Contains 1789404 records and 11 fields with names like;
- transaction_id: Unique identifier for each transaction.
- transaction_date: Date when the transaction occurred
- transaction_time: Time of the transaction
- transaction_qty: Quantity of products purchased in a transaction.
- store_id: Unique identifier for each store location.
- store_location: Name or description of the store's physical location.
- product_id: Unique identifier for each product sold.
- unit_price: Price of a single unit of the product in the transaction.
- product_category: General category to which the product belongs
- product_type: Specific type or variant of the product
- product_detail: Additional details about the product


## Problem Statement: 

Here are the questions/insights your manager would like to see
1) We only want to look at the recent 3 months sales, nothing more. 
2) I know we have a variety of products, but we only want to focus on Coffee and Tea. Not loose tea, coffee beans, just Coffee and Tea.
3) How did our locations perform sales-wise with Coffee and Tea? Did you see any correlations based on location or type of coffee/tea? 
4) Do we have a best seller? Is there some coffee or tea that you'd recommend we remove? 
5) Can we see how each service size (Small, Regular, Large) performed sales-wise for coffee and tea? We want to see what our customers are mostly buying so we can possibly move our prices around.


## Data Prepartation:
 I cleaned the data prior to the analysis to be confident in the insights drawn from the data. No duplicate were found. 
 
 - There was no column for service size, so I created a conditional column for Service Size.

   ![](First_Weekly_Analysis.png)

- Created a calculated column for Transaction_month and transaction year
  
  ![](newcolumn.png)

## The Report:

  

  
