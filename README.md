# Prediction of Product Sales 

## overview:
The project uses product data to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales.

## Data Insights:
- SUPERMARKET 1 gets highest sales Prices between 100 -200 have higher sales
- Most items sell between 1500 to 2500
- Medium outlet size have higher sales

## Summary of the model and its evaluation metrics:
Two models have been used, both evaluated with R-squared & RMSE:
- Linear Regression model
- Regression Tree

## Final recommendations: 
- Recommendation is to use the Linear Regression Model
- Regression Tree Model has a perfect fit to the training data (R-squared of 1) and a low RMSE. This looks like overfitting, the model may not perform well on unseen data. 2) the Linear Regression Model has a lower R-squared, but is less prone to overfitting, and the RMSE suggests reasonable accuracy in predicting sales.

![Screenshot 2023-05-19 at 10 30 19 AM](https://github.com/milkadata/Prediction-of-Product-Sales/assets/129556665/b1b2f496-7324-4d74-a428-a20a92e5e5e8)

![Screenshot 2023-05-19 at 10 30 35 AM](https://github.com/milkadata/Prediction-of-Product-Sales/assets/129556665/77cabb09-22e7-466c-93f5-641d66d1e340)
