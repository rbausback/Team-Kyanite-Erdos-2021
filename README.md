# Team-Kyanite-Erdos-2021
Project focusing on forecasting the S&amp;P 500 for 2020-2021 using a LSTM based neural network and sentiment data from Reddit/news.

Description: Our model is a single layer LSTM-based neural network. The model takes a naive volatility calculated from 1 minute data for the S&amp;P 500 index (with ticker SPY), as well as an average sentiment score from reddit for SPY during that minute, in order to predict the volatility in the next minute. This was done the entirety of 2020. 

The respository is divided into data scraping/preprocessing and neural network construction/training. The preprocessing folder then includes subfolders for the type of data being scraped/preprocessed. 

The code is written in jupyter notebook format in Python. The neural network was constructed using Keras. 
