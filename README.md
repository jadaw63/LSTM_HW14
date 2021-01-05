# LSTM_HW14
## Homework 14  - LSTM Stock Predictor Using Closing prices and the Fear and Greed Index


### Which model has a lower loss?
The stock predictor using the closing prices has the lowest loss at 0.0079 versus the model with the feer and greed index at 0.0860.

### Which model tracks the actual values better over time?
The Closing prices model has a much better fit, you can see this on the graph when model is plotted against the actual and predicted values.

### Which window size works best for the model?
The window was adjusted to equal 5 and the closing prices model loss was 0.0236 compared to the feer and greed index model of 0.0943. 
The ased window size seems to increase the loss for the closing prices model and the fear and greed index model. The optimum window size seem s to be around 10.