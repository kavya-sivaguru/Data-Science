# OVERVIEW:

Material back order is a common problem in supply chain systems which affect the efficiency and service level of the inventory system. 
Machine learning can identify patterns related to back orders before customers place orders while predictive analytics enables maximum products to get in the hands of customers at the lowest cost to the organization. 

Production can then make adjustments to minimize delays, while customer service can provide accurate dates to keep customers informed and satisfied. 
The objective of this Capstone project is to pinpoint the items most likely to experience a shortage before it happens in order to boost the business' overall performance.

Domain of Project : E-Commerce (Supply Chain)

## BUSINESS PROBLEM STATEMENT

When a customer orders a product which is not available in the store or out-of-stock temporarily or due to lack of supply, the customer decides to wait until the desired product is available and there is a guaranteed delivery, then this scenario is called Backorder of the specific product. If the back orders are not handled promptly , there is a high chance of losing a customer to its competitor , along with impact on revenue ,share market price etc. On the other hand, taking actions to satisfy or reduce back orders puts tremendous amounts of pressure on the different stages of supply chain management. Taking steps to satisfy or reduce back orders will lead to increased labor/production/transport/Warehouse costs etc.

## PROJECT OUTCOME:

The objective of this project is to pinpoint the items most likely to experience a shortage before it happens in order to boost the business' overall performance. Machine Learning can identify patterns related to back orders before the customer orders. With this, the production can adjust to minimize delays for customer service and provide accurate dates to keep the customers informed.

This predictive analysis approach gives the company ample time to react and enables them to satisfy the demands of customers and smooth the supply chain process. The task at hand is classifying whether a product will go to backorder or not for a given input data. This is a Binary Classification Problem hence consists of two target values :
Yes: Represents that product will go to backorder.
No: Represents that product will not go to backorder

  
## APROACH:

The main goal is to predict the whether a product comes in backorder or not based on different factors available in the dataset.

· Data Exploration : Exploring dataset using pandas,numpy,matplotlib and seaborn.

· Data visualization : Ploted graphs to get insights about dependent and independent variables.

· Feature Engineering : Removed missing values and created new features as per insights.

· Model Selection : Tested all base models to check the base F1 score. 

· Model Evaluation : Calculate Performance Metrics to check whether a model is a good fit or not.

· Model Optimization :  Perform Hyper parameter tuning using GridSearchCV.

## Dataset Description -

The dataset used in this article contains 16,87,861 records in the train dataset and 2,42,075
records in the test dataset. 
Each record has 23 columns each referring to a concrete attribute. 

### Data Dictionary -

a) SKU : Product ID <br>
b) national_inv : Current inventory levels of components. <br>
c) Lead_time : Transit time of the product which means how long it takes for a shipment to be delivered at its final destination after it has been picked from the start point. <br>
d) in_transit_qty : Amount of products in transit from source. <br>
e) Forecast columns: Tells about the forecast sales of the products for next 3,6,9 months. <br>
f) Sales columns : Sales quantity for prior 1,3,6 and 9 months time period. <br>
g) min_bank : Minimum amount of stocks recommended. <br>
h) Pieces_past_due : Amount of parts of the product overdue if any. <br>
i) Performance average : Product performance over past 6 months and 12 months respectively. <br>
j) deck_risk,oe_constraint,ppap_risk,stop_auto_buy,rev_stop : Yes or No flags set for the products. <br>
k) went_on_backorder : Target Variable <br>

### Feature Engineered Features:
1. Shortage
2.  Demand
3. Sales_Avg
4. Forecast_Avg
5. Performance
6. Performance_Avg
7. Overdue
8. Sale_Performance
9. Orders

### REFERENCES:

Reference documents of CRISP-DM:
a. https://paginas.fe.up.pt/~ec/files_0405/slides/02%20CRISP.pdf 
b.https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining 

Classification concepts - 
https://www.analyticsvidhya.com/blog/2021/09/a-complete-guide-to-understand-classification-in-machine-learning/ 
Back-Orders - 
https://www.thefulfillmentlab.com/blog/how-to-prevent-backorders
https://www.investopedia.com/terms/b/backorder.asp#:~:text=A%20backorder%20is%20an%20order,manufacture%20more%20of%20the%20product.
https://journalofbigdata.springeropen.com/articles/10.1186/s40537-020-00345-2.
