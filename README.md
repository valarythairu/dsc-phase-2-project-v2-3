## House Pricing Prediction Project

## Author: Valary Thairu

### Overview
I have been tasked with providing a real estate agency with data to help set house prices. I aimed to explore the Kings County House Sale dataset to determine how different factors affect house prices. This task is also meant to assist homeowners in finding out which home renovations increase the sale rate of their homes and have the highest effect on their property value. I achieved my goal using multiple linear regression which provided the factors that affect house prices the most. Based on my analysis I have established that square-foot living space in a home has the highest positive effect on the sale price of a house. I have made some recommendations on the factors affecting a house's sale price, which also helps homeowners know which home renovations they should focus on.

### Business Understanding
A real estate agency wants to find out among the different factors that form a house which factors affect the price of homes in North-Western County. Using linear regression I will use the dataset provided to find that out.

### Main Objective
To identify the factors that are affecting housing sale prices.

### Specific Objectives
1. To find the relationship between a house's sale price and different factors of a house.
2. To assist homeowners in finding out which home renovations affect the house's sale price.
   
### Data Understanding
The data we are using is from the King County House Sale Dataset, it contains the various factors of a home including its sale price. 
Analysis of this dataset contributes to the success of house pricing. In this analysis, I will find the relationship between different factors
contributing to a house and its sale price.

### Data Analysis
In this section:
1) I check the data for duplicates.
2) I checked the data and identified and removed outliers.
3) I checked for missing values and replaced the values in the columns in different ways. There are columns where I used the backfill method while in the others I filled the missing values with zero, better explained in the notebook.
4) I used visualizations to display the cleaned data to be able to identify and analyze trends in datasets.

### Modelling 
I used linear regression models to identify the relationships between house sale prices and the different factors of a house affecting it.

### Regression results
1. The model is overall statistically significant with an f-statistic p-value well below 0.05.

2. The coefficient 'sqft_lot' is not statistically significant as its p-value is well above 0.05.

3. The remaining coefficients are statistically significant with P values well below 0.05.

4. Based on the summary model it can summarize as follows:
y= c + beta1x1 + beta2x2 ...... beta19x19

where; c is the Intercept
beta1 - coefficient of the variable
beta2 - coefficient of the variable etc. upto beta19

### Conclusions.
1. This dataset provides insightful data that is very helpful to realtors and homeowners.
2. The square foot living space in the home(sqft_living) according to the model has the highest positive effect on a house's sale price in that a bigger sqft_living increases a house's sale price.
3. The square foot of the basement (sqft_basement) has had the second highest positive effect on the house's sale price.
4. The variables in the data which were tested for their relationship with price each had a different effect on the house's sale price some had negative effects on price others had positive effects on price. So these are the variables that had a positive effect on the house's sale price: 'sqft_living', 'sqft_basement', 'sqft_above', 'floors', 'bathrooms', 'condition', and 'sqft_living15'.
#### These factors/variables have been explained well in the notebook what they represent.







