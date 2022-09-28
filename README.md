# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Business Goal 

 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.



<!-- You can include any other section that is pertinent to your problem -->

## General Information
Build advanced linear regression model to identify the features that helps in predicting the price of the model. Have used Lasso and rigde regression to sovle the problem.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Optimal lambda value is as below for selecting top 10 features that can predict the price of the house::
Ridge - 20
Lasso - 0.0005
Mean squared error is as below:
Ridge - 0.01833
Lasso - 0.01823
The mean suared error for lasso is sligtly lower than Ridge. In lasso some of the coefficients becomes zero which helps us eliminate features. Based on lasso regression GrLivArea,OverallQual,GarageCars,Foundation_PConc,OverallCond,MSZoning_RL features affect the price of the house.
Below features are negatively correlated to sales price so the sales price will decrease.
BsmtQual_Gd BsmtExposure_no_basement BsmtFinType1_Unf BsmtQual_TA
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
numpy, pandas,sklearn,seaborn,matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




## Contact
Created by [@skkage] - feel free to contact me!

