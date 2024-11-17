### Stock Market Analysis and Prediction

* The backend API consumes the Yahoo Finance data for the ticker codes submitted.
* It identifies the 100 days and 200 days of moving Average and plots the chart.
* It uses the LSTM (Long Short Term Memory) deep neuron network to train the data.
* I am using Tensorflow and Keras to train and save the model.
* Once the model is trained, I am testing it with the test data.
* I am evaluating the model performance with MSE, RMSE and R Squared metrics.
--------------------
* This code has been integrated in Python / Django application to produce as a restful URL which can be consumed in Front end application.
* The application displays the relevant charts for 100, 200 days of moving average predictions and the final overall prediction.
* Also it displays the model evaluation units. 
