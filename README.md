# AdvancedLinearRegression

# Problem Statement
### A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

### The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

### The company wants to know:
### Which variables are significant in predicting the price of a house, and

### How well those variables describe the price of a house.

### the optimal value of lambda for ridge and lasso regression.

# Interpretation of Results:

### The management can make use of this model on the future test datasets to get the predicted sales values of different houses from this model. (Ridge Regression model). It's is performing really well on test as well as train datasets.

#### If they want to interpret the results of this model and get to know bout the most important drivers, its as follows:
    
#### The most important top 10 variables which determine the pricing of a house are:
   1. GrLivArea: Above grade (ground) living area square feet
   2. 2ndFlrSF: Second floor square feet
   3. TotalBsmtSF: Total square feet of basement area
   4. LotArea: Lot size in square feet
   5. OverallCond_7: Good Overall Condition
   6. 1stFlrSF: First Floor square feet
   7. YearBuilt: Original construction date
   8. YearRemodAdd: Remodel date (same as construction date if no remodeling or additions)
   9. Fireplaces: Number of fireplaces
   10. Central air conditioning= Yes
