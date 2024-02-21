# Advance Regression Assignment

## House Price Prediction Assignment

### Problem Statement:
 A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

 Essentially, the company wants to know —

    Which variables are significant in predicting the price of a house, and

    How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

## Conclusions

### Comparision between Training and Testing dataset:

	|Metric	|		|Linear Regression|	|Ridge Regression|	|Lasso Regression|
|-|	|-------|		|-----------------|	|----------------|	|----------------|
|0|	|R2 Score (Train)|	|0.939759|		|0.936456|		|0.886991|
|1|	|R2 Score (Test)|	|0.908757|		|0.913474|		|0.890848|
|2|	|RSS (Train)|		|8.990495|		|9.483481|		|16.865737|
|3|	|RSS (Test)|		|5.598378|		|5.308977|		|6.697230|
|4|	|MSE (Train)|		|0.094818|		|0.097383|		|0.129868|
|5|	|MSE (Test)|		|0.114236|		|0.111244|		|0.124945|


 The five most important predictor variables in our model are:
 
 OverallQual, OverallCond, Fireplaces, FireplaceQu_Gd, LotFrontage

