# MorningstarStockPricePrediction_ReccurentNueralNetworks_Project

This project aims to perform the following:

1) Data Collection: Collect historical stock data for Morningstar.
2) Data Preprocessing: Prepare the collected data for training by handling missing values,noise values, normalizing data, and creating time series sequences and ensuring the data is suitable for input into an RNN.
3) Model Building: Employ an RNN architecture suitable for time series prediction and using Long Short-Term Memory (LSTM) to capture long-term dependencies in the data.
4) Training: Split the dataset keeping the stock records of last 1 year as the test set and rest of the records starting from 2005 as the training set.
5) Visually analysing the performance of the model and check if our model was able to accurately predict trends in our data.
6) Evaluation: Evaluate the model's performance using metrics such as Mean Squared Error (MSE) and R2 score.
