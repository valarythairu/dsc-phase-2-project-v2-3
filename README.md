## House Pricing Prediction Project

## Author: Valary Thairu

### Overview
I have been tasked with providing a real estate agency with setting house prices. I aimed to explore the Kings County House Sale dataset to determine how different factors affect house prices. This task is also meant to assist homeowners in finding out which home renovations increase the sale rate of their homes and have the highest effect on their property value. I achieved my goal using multiple linear regression which provided the factors that affect house prices the most. Based on my analysis I have established that square-foot living space in a home has the highest effect on the sale price of a house. I have made some recommendations on the factors affecting a house's sale price, which also helps homeowners know which home renovations they should focus on.

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

### Conclusions.
1. This dataset provides insightful data that is very helpful to realtors and homeowners.
2. The square foot living space in the home(sqft_living) according to the model has the highest positive effect on a house's sale price in that a bigger sqft_living increases a house's sale price.
3. The square foot of the basement (sqft_basement) has had the second highest positive effect on the house's sale price.

### Recommendations
1. The real estate agency should increase square foot living space in home as it increases sales prices of the homes, they should also focus on increasing square foot of the basement. These two factors have the highest positive effect on houses sale price hence are very important.
2. Consider other algorithms beyond multiple linear regression.
3. As according to my findings, homeowners should also focus on the number of bathrooms, square-foot living space in the home, Square footage of the house apart from the basement, Square footage of the basement, and number of floors when they want to do home renovations as these factors affect the price of houses positively.





