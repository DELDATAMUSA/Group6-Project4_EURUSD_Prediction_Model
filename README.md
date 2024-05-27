# Group6-Project4_EURUSD_Prediction_Model
Data preparation and cleaning
Data range: Start from 2010 and ends in 2024.
Define and execute the result function to verify data stored in SQL database.

Calculate the return column and clean the data
Define the features and target variables
Split the data into training and test 

standardise your training and test datasets using StandardScaler from sklearn.preprocessing.
Using a Support Vector Regression (SVR) model with a radial basis function (RBF) kernel can be a great choice for analyzing the relationship between x and y.
# Initialize the SVR model with RBF kernel
svr = SVR(kernel='rbf')
# Fit the model on the training data
svr.fit(X_train_scaled, y_train)

Calculate Mean Squared Error and R-squared
Compute the Mean Squared Error (MSE) to evaluate the average squared difference between the actual and predicted values.
Compute the R-squared (R²) to measure the proportion of variance in the dependent variable that is predictable from the independent variable(s).

