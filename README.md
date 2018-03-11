# Rossmann-Sales-Prediction
![ASW_Corp_Site_Header_Our_Portfolio_Rossmann.jpg](https://user-images.githubusercontent.com/32555702/37235455-ada03b6a-23b3-11e8-9a53-0df7a4b704bc.jpg)
### *Notice: I mostly used PLOTLY to visualize my data in this notebook, but the plotly plots aren't displaying on github.*

Kaggle Competition:
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

We're accepting Rossmann's challenge to predict 6 weeks of daily sales for 1,115 stores located across Germany. Reliable sales forecasts enable store managers to create effective staff schedules that increase productivity and motivation. By helping Rossmann create a robust prediction model, we will help store managers stay focused on what’s most important to them: their customers and their teams!

## Table of Contents
1. Import Packages
2. Data Preparation
  2.1 Load Dataset
  2.2 Dealing With Missing Values
     2.2.1 Count missing values in each dataset
     2.2.2 Remove features with high percentages of missing values
     2.2.3 Replace missing values in features with low percentages of missing values
  2.3 Date Extraction
  2.4 Joining Tables
  2.5 Drop Subsets Of Data Where Might Cause Bias
  2.6 Feature Engineering
  2.6.1 Create new variable "AvgSales"
  2.6.2 Create new variable "AvgCustomer"
  2.6.3 Transform Variable "StateHoliday"
3. Exploratory Data Analysis
  3.1 Correlation Heatmap
  3.2 Sales Distribution
  3.3 Customer Distribution
  3.4 Sales Over Time
  3.5 Sales Over Days Of A Month
  3.6 Sales Over Weeks
  3.7 Sales By Store Type
  3.8 Sales By Assortment
  3.9 Sales vs. Number Of Customers
  3.10 Sales vs. Competition Distance
  3.11 Sales By Promotion
  3.12 Pair Plot
4. Store Sales Prediction (Regression Models)
  4.1 Linear Regression (OLS)
  4.2 Bayesian Ridge Regression
  4.3 LARS Lasso Regression
  4.4 Decision Tree Regression
  4.5 Random Forest Regression
  4.6 K-Nearest Neighbors Regression
  4.7 Model Selection
  
There actually will be part 5 coming ----
I'm working on an ARIMA time series model to tackle the prediction. 
Please see file "Rossmann Store Sales Prediction(ARIMA)" in my "Time Series Analysis" repository =]
