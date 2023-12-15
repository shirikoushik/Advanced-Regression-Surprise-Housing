# Advanced House Price Regression
Predicting house prices using advanced regression techniques such as Ridge and Lasso.

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the 'test.csv' file uploaded in the repository.

The company is looking at prospective properties to buy to enter the market. This repository builds a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know: -Which variables are significant in predicting the price of a house? -How well those variables describe the price of a house?

Using GridSearchCV the model arrives at a final optimum lambda to determine the house prices using ridge and lasso regression.
For lasso optimal alpha 0.001 and for ridge alpha 0.9
After comparing both models, these are the best features explaining the dataset.
- CentralAir: Central air conditioning
- BsmtCond: the general condition of the basement
- BsmtQual: the height of the basement
- BsmtExposure: Refers to walkout or garden level walls
- HalfBath: Half baths above grade
- TotalBsmtSF: Total square feet of basement area
- LandSlope: Slope of property
