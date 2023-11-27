# Sales-Forecasting-Model

## Goal:

The primary objective of this project is to leverage time series forecasting techniques to accurately predict shampoo sales for the upcoming year. By applying advanced forecasting models, the goal is to provide stakeholders with insights that facilitate informed decision-making and strategic planning for inventory management and sales optimization.


## Approach:

1. Explored and visualized the Sales data.
2. Applied the Augmented Dickey-Fuller (ADF) test to check if the time series data is stationary or not and applied  differencing to make it stationary.
3. Examined the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots to identify potential values for p, d,  q , P, Q, D in the SARIMAX model.
4. Split the time series data into training and testing sets. This allows you to train the model on historical data and evaluate its performance on unseen future data.
5. Fit a  (SARIMAX) model using the identified values of p, d, q, P, Q, D
6. Perform hyperparameter tuning to find the best combination of parameters (p, d, q, P, D, Q) that minimizes the Akaike Information Criterion (AIC).
7. Evaluate the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
8. Use the trained model to generate future predictions for a specified number of time steps.
