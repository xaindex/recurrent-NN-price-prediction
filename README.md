# Recurrent neural network for price prediction

In this case study, we use Deep Learning, Recurrent Neural Networks with Long Short-Term Memory(LSTM) layers to predict the price of Google stock. LSTM is a more sophisticated version of RNN that addresses the Vanishing Gradient Problem that RNNs often suffer from. 

# Data Analysis 1: Google Stock Price Prediction
We have used Google stock price data, publicly available and downloaded from Yahoo Finance. For training the model, we used stock prices for the period of 2016-2020 and used it to predict stock prices for January 2021. 

Google Stock Price Development Graph (Training Data)
<p align="left">
  <img src="https://github.com/TatevKaren/recurrent-neural-network-pricing-model/blob/main/Google Stock Price Development.png?raw=true"
  width="600" height="300">
</p>
<br>
<br>

## Google Data Preprocessing

In order to prepare the data to train and test the RNN model we have performed certain data preprocessing steps using Tensorflow, Keras, Pandas, and Scikit-Learn libraries.
<p align="left">
  <img src="https://github.com/TatevKaren/recurrent-neural-network-pricing-model/blob/main/data/Data transformation.png?raw=true"
  width="380" height="220">
</p>
<br>
<br>

## Prediction Results

Comparing the real Google stock values and predicted Google stock values that are generated using the RNN model for the test period, the first month of 2021. RNN, based on 5 LSTMs, could properly predict all upward and downward trends as we see that the red line corresponding to the predicted stock prices follows the same pattern as the blue line, which corresponds to the real stock prices. 
<br>
<p align="left">
  <img src="https://github.com/TatevKaren/recurrent-neural-network-pricing-model/blob/main/Prediction_Results.png?raw=true"
  width="600" height="400">
</p>
<br>
<br>

# Data Analysis 2: Bitcoin Price Prediction

The same method can be applied to different financial instruments such as Bitcoin. 
<br>
<p align="left">
  <img src="https://github.com/TatevKaren/recurrent-neural-network-pricing-model/blob/main/Bitcoin_Price.png?raw=true"
  width="600" height="380">
</p>
<br>
<br>

## Bitcoin Data Preprocessing

In order to prepare the data to train and test the RNN model we have performed certain data preprocessing steps using Tensorflow, Keras, Pandas, and Scikit-Learn libraries. 
<p align="left">
  <img src="https://github.com/TatevKaren/recurrent-neural-network-pricing-model/blob/main/bitcoin_data/Bitcoin_data_transformation.png?raw=true"
  width="600" height="250">
</p>
<br>
<br>

## Prediction Results

Comparing the real Bitcoin price values and predicted Bitcoin price values that are generated using the RNN model for the test period. 
<br>
<p align="left">
  <img src="https://github.com/TatevKaren/recurrent-neural-network-pricing-model/blob/main/Bitcoin Price Prediction.png?raw=true"
  width="600" height="400">
</p>
<br>
<br>

## Contact
Feel free to contact us if there is any question (tech@xaindex.ai).
