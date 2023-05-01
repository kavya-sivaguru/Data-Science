# PROBLEM STATEMENT

A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month.
The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.

Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

## DATA DESCRIPTION:

User_ID -	User ID <br>
Product_ID - Product ID <br>
Gender - Sex of User <br>
Age - Age in bins <br>
Occupation - Occupation (Masked) <br>
City_Category - Category of the City (A,B,C) <br>
Stay_In_Current_City_Years - Number of years stay in current city <br>
Marital_Status - Marital Status <br>
Product_Category_1 - Product Category (Masked) <br>
Product_Category_2 - Product may belongs to other category also (Masked) <br>
Product_Category_3 - Product may belongs to other category also (Masked) <br>
Purchase - Purchase Amount (Target Variable) <br>

## APROACH:

The purchase column is the Target Variable, so Univariate Analysis and Bivariate Analysis was performed w.r.t Purchase.

· Data Exploration : Exploring dataset using pandas,numpy,matplotlib and seaborn.

· Data visualization : Ploted graphs to get insights about dependent and independent variables.

· Feature Engineering : Removed missing values and created new features as per insights.

· Model Selection : Tested all base models to check the base RMSE.

· Model Evaluation : Calculate Performance Metrics to check whether a model is a good fit or not.

· Model Optimization : Perform Hyper parameter tuning using GridSearchCV.


### EDA PROCEDURE FOLLOWED:

Checked Purchase Distribution

Checked for missing values in the data

Checked for unique values in data

Checked for outliers

Analysis by Gender, Marital Status, occupation, occupation vs purchase, purchase by city, purchase by age group, etc

Dropped unnecessary fields

Converted categorical data into integer using map function (e.g 'Gender' column)

Missing value treatment

Renamed columns

Filled nan values

Mapped range variables into integers (e.g 'Age' column)


