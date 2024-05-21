# Surprise_Housing_Sale_Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

# Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

# Methods Used :
First I imported some impotant python libraries
Then I loaded the data file
Basic checks on the datasets
Cleaning the data by Nan values handling, missing values handling and outliers removal
Removing colums with Null above 15 %
Imputation of missing values with None
EDA
Dropping columns with no or very less variance
Working with Years columns
Checking skewedness and fixing it
Plotting counter plots , box plots,pair plots comparing different columns
Findings from plot mentioned
Checking corelation from the plots
Train-Test split
Double checks for Nans and fixing them
Adding dummy variables
Linear regression on both train and test
Result for test not good so removing columns with high VIF
Building first Model.
Find multicollenearity so another model to be developed
Final Model develop
Final model evaluation
Linear model coeffs and features and observation
Residual analysis for test and train
lasso regression
Ridge regression
Ridge and linear model coeffs and features and observation and optimal value of lambda/alpha
Train evaluation with alpha
Test evaluation with alpha
Comparisons of Linear, Lasso and Ridge metrics and final values for R2, adj R2, RSS, MSE on both Train and test for Linear , Ridge and lasso
Conclusions and observation are in this notebook as you go thru it and final observation at bottom

## Conclusions:

Observations
The model identifies 32 significant features.
Features are ranked by the magnitude of their coefficients, with the most significant feature listed first.
After applying Ridge and Lasso Regression for regularization, the coefficients remain close to those produced by Linear Regression, exhibiting only slight variations.
Despite these minor variations, the order of feature significance remains consistent across all models.
The R² Score, RSS, and MSE are comparable across the Linear Regression, Ridge, and Lasso models.
Lasso Regression achieves marginally better scores compared to both Ridge and Linear Regression.

Upon evaluating various models, it's evident that certain features play a pivotal role in elucidating the selling price of houses:
1. MSSubClass_90 (Type of Dwelling - DUPLEX - ALL STYLES AND AGES)
2. MSSubClass_120 (1-STORY PUD - Planned Unit Development - 1946 & NEWER)
3. RoofMatl_Membran (Roof Material - Membrane)
4. MSZoning_RL (Residential with Low Density - General Zoning Classification)
5. MSZoning_FV (Floating Village Residential)
6. MSZoning_RH (Residential High Density)
7. MSZoning_RM (Residential Medium Density)
8. Condition2_PosA (Adjacent to Positive Off-Site Feature)
9. RoofMatl_WdShngl (Roof Material - Wood Shingles)
10. Neighborhood_NoRidg (North Ridge)
11. OverallQual (Excellent Overall Quality)
These features, ranging from dwelling types and zoning classifications to roofing materials and neighborhood designations, collectively contribute significantly to the explanation of house sale prices. Among them, 'OverallQual' specifically encapsulates the exceptional quality aspects of a property, encompassing superior craftsmanship, high-end materials, and an impressive overall aesthetic, which notably influences the property's market valuation.

## Acknowledgements:

1.Upgrade Course materials, recorded sessions
2.Upgrade live sessions
3. Upgrad Teacher - Akaashdeep Makkar
4. Upgrad Personal Coach - Mukesh Sir/Dinesh Sir

##  Contacts

###### Developer : Susrita Das
###### Group : C61
###### email : susrita.das@gmail.com
###### Phone no. +91 8584097202
###### https://github.com/SusritaDas/Surprise_housing_sale


```python

```
