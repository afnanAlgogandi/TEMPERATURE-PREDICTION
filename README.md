# TEMPERATURE PREDICTIO
 developed a model that can predict air temperature according to atmospheric pressure.
 
In this project we used "Saudi Arabia weather history" dataset from Kaggle.
We took 2 attributes (temp, barometer), type(int64, float64), and 5000 random examples,
80% for training and 20% for testing.

We used 3 different models:
1. Linear Regression
2. Batch Gradient Descent
3. Polynomial Regression

Tried different polynomial degrees, learning rates, and number of iterations.

We compared them by using:
1. Mean absolute error (MAE)
2. Mean sum of squares error (MSSE)
3. Root mean square error (RMSE)
