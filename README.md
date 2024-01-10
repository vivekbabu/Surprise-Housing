# Surpise Housing
> Machine Learning project for predicting housing price

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

Business Goal 

 

We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
We have built Ridge and Lasso regression models and below is the summary for model performance, key predictive features and the optimal lambda values

#### Model Performance
For **Ridge** key preditive features were
<br>- **GrLivArea**
<br>- **TotalBsmtSF**
<br>- **OverallQual_Very Good**
<br>- **1stFlrSF**
<br>- **OverallQual_Excellent**
<br>- **2ndFlrSF**
<br>- **Neighborhood_Crawfor**
<br>- **LotArea**
<br>- **Neighborhood_MeadowV**
<br>- **YearRemodAdd**

For Lasso key predictive features were 
<br> - **GrLivArea**
<br> - **OverallQual_Excellent**
<br> - **TotalBsmtSF**
<br> - **OverallQual_Very Good**
<br> - **YearBuilt**
<br> - **Neighborhood_Crawfor**
<br> - **GarageCars**
<br> - **Neighborhood_Somerst**
<br> - **Neighborhood_MeadowV**
<br> - **LotArea**

#### Optimal Lambda Values

The optimal **lambda** value, which controls the trade-off between bias and variance in our models, was found to be **9** for Ridge regression and **0.004** for Lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Pandas Dataframe
- Seaborn
- Linear Regression


## Contact
Created by [@vivekbabu] - feel free to contact me!
