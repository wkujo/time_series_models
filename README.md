# time_series_models

Various RNN models to predict information about stocks (data from Kaggle). All models were created using the information for stock A. 


Model 1 - Univariate prediction using last 20 days of stock highs to predict next stock high using multi-layer bidirectional LSTMs. 


Model 2 - Multivariate prediction using last 20 days of stock highs, lows, and opens to predict next stock high using multi-layer bidirectional LSTMs. 


Model 3 - Multivariate prediction using last 20 days of stock highs, lows, and opens to predict next 4 days of stock highs, lows, and opens using a standard LSTM encoder decoder for training and inference. 
