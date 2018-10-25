# Cryptocurrency-Prediction-using-RNNs
This repository contains binary prediction of whether prices are going to rise or fall in a time window of 3min from a data collected in the previous 60min time window.

Dataset Description : 

* BCH-USD - Bitcoin
* BTC-USD - Bitcoin Cash
* ETH-USD - Ethereum
* LTC-USD - Litecoin

* Each one of these __CryptoCurrencies__ are taken-up in .csv dataformat and have following features : 
    time(int),Open, High, Low, Close, Volume

* We are only considering **Close** and **Volume** features of each currency as our data for prediction.

* Time window for data collection(serving as base-data for prediction) is taken up to be 60 minutes with prediction time window 3 minutes implying __Sequence Lengths__ to be __60__.
