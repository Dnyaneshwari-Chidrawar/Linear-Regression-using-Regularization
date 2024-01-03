# Housing Company (Linear Regression using Regularization) 
> The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market.   
- The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.   
- For the same purpose, the company has collected a data set from the sale of houses in Australia.  
- The company wants to know:  
1. Which variables are significant in predicting the price of a house, and   
2. How well those variables describe the price of a house.

## Conclusions
- Regularization helps to reduce Overfitting problem  
- In this case Lasso Regression is better than Ridge Regression.  
- Accuracy for both the regression model is almost same. But loasso regression helps in feature selection too. Lasso makes the model sparse and simpler.   
- Top features are for Ridge Regression : GrLivArea, RoofMatl_CompShg, RoofMatl_Membran, RoofMatl_Metal, RoofMatl_Roll  
- For Lasso Regression : GrLivArea, LotFrontage, Condition2_PosN  

## Technologies Used
- ydata_profiling - version 23.2.1  
- ipywidgets - version 8.1.1  

## Acknowledgements
- This project was based on [Linear Regression](https://en.wikipedia.org/wiki/Linear_regression).
- This project was inspired by [seaborn](https://seaborn.pydata.org/index.html).


## Contact
Created by [Dnyaneshwari Chidrawar](https://github.com/Dnyaneshwari-Chidrawar) - feel free to contact me!
