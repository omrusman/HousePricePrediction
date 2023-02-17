# House Price Prediction using R Programming

This project is about the analysis of the valuation of the property (Sale Prices). The main aim of this analysis is to predict the price of different properties located in certain areas. There are two algorithms required to do this analysis, a primary and a secondary algorithm. R programming language has been chosen for this analysis and R studio IDE is chosen for programming because it provides better statistical computing and graphics.

An Ames Housing Dataset is chosen from Kaggle. This dataset includes the different aspects of property (zone, area, shape, land, neighborhood, condition, facilities, build year, etc) and how it affects the price of the property. 

These are some packages required to run this project. 

• ggplot2 – A graph plotting package. 

• gridExtra – It provides more functionality for graph plotting. 

• moments

• devtools – It helps in package development. 

• corrplot – It provides functionality for correlation matrix graph. 

• dplyr – It helps in data manipulation. 

• randomForest – It helps to create a random forest model. 

• metrics – It provides different metrics for regression, classification, binary, and time series tasks. 

# Modeling and Analysis

Two machine learning algorithms are used in this analysis:
1. Random Forest.
2. Multiple Linear Regression. 

For checking if the training model is trained perfectly, there is a method to check by taking the data from testing data which is not available during the training phase. This unseen data helps to evaluate the accuracy of the model. The method used for evaluating the accuracy of the model is called Cross-validation. There are certain metrics used in Cross-validation: 
1. Root Mean Square Error (RMSE)
2. Mean Absolute Error (MAE)
3. R2 Error

## 1. Random Forest
The root means square value is 0.30 which shows the difference between the actual and predicted value. It provides the average of prediction errors done by the trained model. The lower the value of RMSE the higher the accuracy of the model. The R square error value is 0.095 which shows the variance of the target variable with the model. The mean absolute error value is 47195 which shows the absolute difference between the actual and predicted value. 

## 2. Multiple Linear Regression
The root means square value is 0.39 which shows the difference between the actual and predicted value. It provides the average of prediction errors done by the trained model. The lower the value of RMSE the higher the accuracy of the model. The R square error value is 0.096 which shows the variance of the target variable with the model. The mean absolute error value is 53382 which shows the absolute difference between the actual and predicted value. 

# Conclusion
This report discusses the statistical analysis of the sale prices of different houses based on different features. Starting from the pre-processing of the data which includes data integration, data cleaning, data transformation, and data reduction. For the modelling part, it was required to use two models (primary and secondary). The primary model applied to the data is random forest regression and the multiple linear regression model is applied as a secondary. The accuracy of  both models is very close to each other, but random forest accuracy is slightly higher than multiple linear regression. For comparing the accuracy of both models two main metrics are used root mean square error and r-square. The results of each model are also discussed and visualized using graph plots.

All the results are shown in the "Coursework1x.nb.html" file. 
