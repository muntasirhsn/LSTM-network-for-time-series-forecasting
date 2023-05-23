# LSTM-network-for-time-series-forecasting
# Introduction 
Long Short-Term Memory or LSTM is a special type of Recurrent Neural Network (RNN) that can be used for time-series forecasting. LSTM networks are capable of learning features from input sequences of data and can be used to predict multi-step sequences. In this example, a simple Vanilla LSTM architecture (an LSTM model with a single hidden LSTM layer and an output layer for prediction) is used for multistep time-series forecasting. For an excellent introduction to LSTMs, look up [Deep Learning for Time Series Forecasting](https://machinelearningmastery.com/deep-learning-for-time-series-forecasting/).
# Getting Started
The LSTM_univariate_multistep_output_github.ipynb file is the main file for running the LSTM model. The publicly available time-series energy usage data of IIT, Delhi is sourced from [here](https://figshare.com/articles/dataset/Energy_dataset_of_IIITD/6007637/1). Infromation on the data can be found in this [article](https://www.nature.com/articles/sdata201915).
Note: The notebook files have been tested on Google Colab. 
# Model
The model is a simple Vanilla LSTM architecture:

![lstm](https://github.com/muntasirhsn/LSTM-network-for-time-series-forecasting/assets/29087240/53bf6770-6330-436a-b717-66221379bacd)
# Farecasting
Multi-step energy usage forecasting (12 weeks) with Vanilla-LSTM with a Root Mean Squared Error (RMSE) of 6.46.
![lstm_rmse](https://github.com/muntasirhsn/LSTM-network-for-time-series-forecasting/assets/29087240/11c8665e-eac3-4e4b-af31-f59c3670880b)




