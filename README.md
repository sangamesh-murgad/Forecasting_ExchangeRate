# Forecasting_ExchangeRate

* Business objective
   - We had a objective to build a reliable predictive model to predict the Exchange rate for USD vs INR, for short term. 

* Data
   - Data was given by the client and the Data was infact taken from the Link: https://fred.stlouisfed.org, the official economic data of Federal Reserve.
   - The data was from 1973 till June 2021, whcich makes it around 48.5 years of data. The complete EDA is in the EDA file.
 
* Problems faced
   - We were of the opinion that predicting reliably meaning keeping the error to less than 1% was a hard task. 
   - As the Time series data which does not have a reccurring pattern is hard to model.
   - The data provided was largely stocastic and the factors that influence the exchange rate are several, such as, International Oil Prices, Balance of Payments, Monetary Policy, etc. and the influence is largely stocastic.
   - Lastly, there is no gaurantee that the past will be the future in case of stocastic timeseries data.
 
* Models built
   - Naive models - Smoothing techniques
   - ARIMA - order (2,1,0)
   - FBPROPHET 
   - ANN
   - LSTM
   - GRU
 
* Model Deployed
   - LSTM model was deployed using Streamlit library
   - The preformance of the model is reasonable
