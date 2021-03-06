![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)
# Project 4 : Microsoft Stock Market analysis and prediction
### Team members: 
 1. Abeer Alzuhair
 2. Razan Alsulieman
 3. Rawan Mohammed Eid
 
 ## Overview
The Project covers:
- Many Python programming concepts
- Programmatically interacting with files and directories
- visualizations
- Data cleaning and EDA
- Machine Learning Forecasting Models
- Models Evaluation (RMSE)
- Prediction Scores.

 ## Problem statement

Microsoft is an American multinational technology company. It develops, manufactures, licenses, supports, and sells computer software, consumer electronics, personal computers, and related services. Its best known software products are the Microsoft Windows line of operating systems, the Microsoft Office suite, and the Internet Explorer and Edge web browsers.


In this project, we will use historical data of the Microsoft Stock market (from 2015) to forecast the stock closing prices for one upcoming year. This is a TimeSeries prediction problem, which we will try to solve using (SARIMAX, Facebook Prophet, RNN LSTM cells (Long Short-Term Memory)) models.
And to evaluate the accuracy of our models we will use the root-mean-square error (RMSE), this metric is commonly used in forecasting, to find the standard deviation of the prediction errors.

 ## Data Description

 - [Data Source](https://www.kaggle.com/rawaneid/microsoft-stock-market-2001-2021)
 - Data Information: Time Series for Microsoft Company Stock Market in a decade (2001 - 2021)


|Feature|Description|
|--|--|
|**datetime**| datetime in UTC referring to when the bar with specified interval was opened|
|**open**|	The price of MSFT when the stock market opens|
|**high**|	The highest price of MSFT during that trading day|
|**low**|	The lowest price of MSFT during that trading day|
|**close**|	The price of MSFT when the stock market closes|
|**Volume**| How many shares of MSFT were traded that day|


## Conclusion
After taking a quick look at Microsoft Stock market, we found that there was a huge change in 2020 maybe due to Covid-19 panedamic , So the first idea was to drop that year and do modeling but the result somehow was subspecies. Therefore, we used the data including 2020 and we have ended with much greater result. We can observe from FB Prohet and RNN LSTM that the stock will increase in the upcoming year. 

From the 3 different models SARIMAX had the worse RMSE score and on the other hand  RNN LSTM cells (Long Short-Term Memory) had better score but Facebook Prophet was on top and took the first place.  However, The unpredicted fluctuation in the stock market makes it hard to make accurate future predictions.

