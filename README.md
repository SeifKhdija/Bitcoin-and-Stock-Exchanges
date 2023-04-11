High-level overview of the steps followed to build a machine learning model to predict the future price of Bitcoin based on the historical price data of Bitcoin and three traditional stock markets. 

1- Preprocess the dataset: Convert the 'Date' column to a datetime data type and set it as the index of the dataframe. Create a new dataframe containing the closing prices of Bitcoin and the three traditional stock markets.

2- Create new features: Create new features that could be useful in predicting the price of Bitcoin. For example, you could create lagged features that represent the previous day's prices for Bitcoin and the three traditional stock markets. You could also create rolling statistics such as the 7-day or 30-day moving average of the prices.

3- Split the dataset: Split the dataset into training and testing sets.

4- Train the machine learning model: Use the training set to train a regression model such as a linear regression, decision tree, or random forest. Use the lagged and rolling statistics features as the inputs and the future price of Bitcoin as the output.

5- Evaluate the model: Use the testing set to evaluate the performance of the model. Calculate metrics such as mean squared error, mean absolute error, and R-squared to assess how well the model is able to predict the future price of Bitcoin.

6- Use the model to make predictions: Once the model has been trained and evaluated, you can use it to make predictions about the future price of Bitcoin based on new data.
