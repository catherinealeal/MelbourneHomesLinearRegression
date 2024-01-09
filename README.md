# Feature Engineering and Linear Regression to Predict Home Price

## Goal 

Create a linear regression model to predict the prices of homes in Melbourne. 

## Feature Engineering 
- Adding a new column that is the distance in kilometers from the center of Toorak to the latitude/longitude of that row.
- Using the latitude / longitude of (−37.841820,145.015986) for the center of Toorak.
- One hot encoding to replace the 'Type' column

## Linear Regression 
- Create a model which predicts the price of a home based on numeric attributes.
- Use the beta-hat calculated in the last step to predict the housing prices for data in melb_data_sold_test
- Create a visualization that shows the absolute error in predictions
  
<img width="441" alt="Screenshot 2024-01-09 at 2 25 02 PM" src="https://github.com/catherinealeal/MelbourneHomesLinearRegression/assets/100166102/91da610f-be46-4fa2-9d14-7470715999fa">

Figure 1: Comparing the actual prices of homes in Melbourne to the absolute error between the model-predicted prices based on the fitted linear regression model and the actual prices.

## Conclusion 
From the histogram, it is evident that this model predicts the prices of homes in Melbourne fairly well based on the fact that the majority of the absolute errors are less than $50,000.

## View full project [here](https://github.com/catherinealeal/MelbourneHomesLinearRegression/blob/main/MelbourneHomesLinReg.ipynb) 
