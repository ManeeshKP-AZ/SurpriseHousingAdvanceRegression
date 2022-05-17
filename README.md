# Project Name
Surprise Housing - Advance Regression Assignment
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## General Information
We are going to build this project with following business goals
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

To Build the model we will follow below mentioned steps -
1. Reading and understanding the data
2. Data preparation 
3. Exploratory data analysis - EDA 
4. Visualizing the data - Numerical, Categorical & Heatmap
5. Splitting the data into tranining and test datasets.
6. Performing Simple Linear regression
7. Performing Advance regression - Ridge & Lasso
8. Building the model
9. Making Conclusions using the final model
10. Model Evaluation


## Conclusions
Since the model accuracy on test and train set for all three models above are similar, we would chose the simpler model. Simple Linear Regression model is fairly complex, hence we would not consider that. Ridge Regression model is fairly complex, hence we would not consider that. Optimum value of lambda for Ridge Regression is 4 Lasso Regression model is simpler, hence we would consider that, since most co-efficients are zero.

From our initial set of columns, few of the major influencers for Sales Pricing are:

OverallCond SaleCondition Neighborhood Functional KitchenQual Exterior1st Condition1 MSSubClass BsmtExposure MSZoning. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python as programming libraries
Following listed libraries for analysis and plot building.
import warnings
warnings.filterwarnings('ignore')

# Import important Python libraries required for analysis and model building
numpy 
pandas 
matplotlib.pyplot 
seaborn 
statsmodels.api 
sklearn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is created as part of UPGRAD Bike Sharing Assignment
Please follow the below mentioned link for more details.
https://github.com/ManeeshKP-AZ/SurpriseHousingAdvanceRegression.git



## Contact
Created by Maneesh KUmar Pandey
