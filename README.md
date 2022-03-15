# Stockprice_Forecasting
This Rshiny app forecasts the stock price change based on previous price data
The project was submitted to the university as a part of the end term exam for Econometrics in the Masters of public policy program. 

Data: 2013 to 2018

Model: ARIMA(7,1,4)

With this app, we can fit an ARIMA model to the dataset having the stock prices of Google from years 2013-18 .The app takes the following inputs as follows:

1)The category of stock price to be forecasted : Opening price, closing price, etc.

2) Choice of Augmented Dickey-Fuller Test for stationarity : Actual, differenced.

3) Choice of correlation function : Auto correlation function , Partial correlation function

4) The parameters of the ARIMA model :

•	p: The number of lag observations included in the model, also called the lag order.

•	d: The number of times that the raw observations are differenced, also called the degree of differencing.

•	q: The size of the moving average window, also called the order of moving average.

#I used the ARIMA model with the lag value of 7 for autoregression, a difference order of 1 to make the time series stationary, and a moving average model of 4.

5) Number of days for which forecasting is to be done

6) Choice of Forecasted values or Forecasted plot.


 

 
