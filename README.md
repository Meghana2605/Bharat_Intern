# bharat_intern
The code is for predicting stock prices using an LSTM model. LSTM models are a type of recurrent neural network that are well-suited for time series data.

The code first loads the stock price data from the fundamentals.csv file. It then extracts the closing price data and scales it to a range of 0 to 1.

Next, the code splits the data into training and testing sets. The training set is used to train the LSTM model, and the testing set is used to evaluate the model's performance.

The code then reshapes the data for the LSTM model. LSTM models expect the data to be in a specific format, which is why the code reshapes the data accordingly.

The code then defines the LSTM model. The LSTM model has one hidden layer with 128 units. The output layer has one unit, which represents the closing price prediction.

The code then compiles the model using the mean squared error (MSE) loss function and the Adam optimizer.

The code then trains the model on the training set.

Once the model is trained, the code makes predictions on the testing set.

Finally, the code plots the closing price data and the predictions.

Overall, the code provided is for predicting stock prices using an LSTM model. It is a relatively simple code, but it can be effective for predicting stock prices with some accuracy.
