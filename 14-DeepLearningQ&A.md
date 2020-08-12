# Which model has a lower loss?
The LSTM stock predictor that uses closing prices has the lower loss of 0.0099 (Epoch 10) vs 0.0324 (Epoch 10) for the FNG model.
# Which model tracks the actual values better over time?
The LSTM stock predictor using closing prices tracks the actual values better over time. Based on the graphs from each ipynb file, the tracking difference is clear.
# Which window size works best for the model?
Using a window size of 1 for the closing price model delivered the closest fit between real and predicted. As the window size increases the closeness of fit decreases for this model. The FNG model does not fit well regardless of the window size.