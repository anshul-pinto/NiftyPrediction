# NiftyPrediction
Predicting the Price of Nifty50 Index
</br>
I implemented a LSTM network using keras. Currently working on improving the model. Current prediction graph is lagging behind the labels because of not accounting for look-back period. Model seems to be overfitting. 
</br>
Ideas to imrove:
1. Use more features including technical analysis indicators
2. Use cross validation
</br>
--> Tradingmodel.ipynb is the current draft
</br>
Currently the LSTM network fits the graph well but I noticed that the predictions are just a delay of the real prices. This model doesn't seem to work well. Next step is to try and figure out a waya to predict the movement rather than the price itself. 

