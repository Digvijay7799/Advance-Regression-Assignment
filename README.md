# Advance-Regression-Assignment
## Problem Statement
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
-  `Which variables are significant in predicting the price of a house.`
-  `How well those variables describe the price of a house.`
-  `Determine the optimal value of lambda for ridge and lasso regression.`

## Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [Conclusions](#conclusions)
* [Libraries Used](#libraries-used)

* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-  Overfitting is observed in Linear Regresion Model
-  Ridge Model
-  Optimal value of lambda for Ridge regression is 0.2
-  Train and Test R2 values are 0.8383 and 0.8152
-  Lasso Model
-  Optimal value of lambda for Lasso regression is 0.0001
-  Train and Test R2 values are 0.82436 and 0.826
-  Top 10 variables that are significant in predicting the price of a house obtained from Lasso regression are:
-  GrLivArea
-  Exterior1st_BrkComm
-  TotalBsmtSF
-  ExterQual_Fa
-  KitchenAbvGr
-  Functional_Maj2
-  GarageCars
-  LotArea
-  Functional_Sev
-  ExterQual_TA

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Libraries Used
-  pandas
-  numpy
-  matplotlib.pyplot
-  seaborn
-  sklearn
-  statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by Digvijay Kadam [@Digvijay7799] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
