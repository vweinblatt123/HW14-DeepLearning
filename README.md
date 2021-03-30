# HW14 - DeepLearning
## LSTM Stock Predictor

I tested multiple values of the key hyperparameters - window size, batch size, and number of epochs. I found the model performed best utilizing window size of 3 (days), a batch size of 4, and 20 epochs.

*Which model has the lower loss?*

The closing price model has the lower loss on the test data - RMSE of 0.0078 vs 0.0696.

*Which model tracks the actual values better over time?*

As seen in the final plots, the closing price model tracks the actual values better over time. This is not suprising, as graphing just the closing prices versus the FNG values shows a very low correlation.

*Which window size works best for the model?*

It appears a lower window size works best for the model as more recent prices best predict future prices. A window on the higher range (near 10) is too large to be predictive while a very small window (< 3) losses important information. A 3 day window appears to be the ideal window size.



