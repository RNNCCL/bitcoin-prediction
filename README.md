In this, first part, I want to show how RNNs can be used for financial time series prediction.

The main code snipset is taken from https://medium.com/@alexrachnog/neural-networks-for-algorithmic-trading-part-one-simple-time-series-forecasting-f992daa1045a

In this tutorial, we will work with prediction of the bitcoin prices.

Trade data is available as CSV, delayed by approx. 15 minutes. It will return the 2000 most recent trades. http://api.bitcoincharts.com/v1/csv/

Following API also retrives the bitcoin prices http://api.bitcoincharts.com/v1/trades.csv?symbol=SYMBOL[&start=UNIXTIME]

The csv file contains 3 fields, unixtime,price,amount

# bitcoin-prediction
# bitcoin-prediction
