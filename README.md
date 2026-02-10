# Stock-Trading-Strategy
Predicting the next day’s stock price based on stock movements and options data from the previous day. The goal is to beat the buy-and-hold trading strategy.
### What data needs to be collected and how you will collect it？
#### For this project, we wish to collect the stock information with following features:
- Stock price (Bid, Ask, Close, Volume, Open_Interest)
- Date
- Strike_Price 
- Expiry_Date 
- Call/Put_Flag
- Greeks & IV
- Implied_Volatility 
- Delta 
- Gamma 
- Vega 
- Theta 
#### The data collected above is all about the stock data but not have the information about the market data such as the interest rate and the VIX. So we wish to also collect the following features:
- Benchmark Indices
- Volatility Indices
- Interest Rates
#### All the data above can be found in the WRDS (Wharton Research Data Services)(https://wrds-www.wharton.upenn.edu/). It contains the OptionMetrics database, which is industrial-level historical option data. We can use the school email to register an account and download the data in CSV format. 
### How do you plan on visualizing the data?
#### We plan to use the following tools to visualize the data:
- Matplotlib
- Seaborn
- Plotly
#### We are thinking of using the following charts to visualize the data:
- Standard OHLC + Volume: to show the Candlestick Chart and Volume Bars.
- Dual-Axis Line Chart: to visualize the Stock Price and Implied Volatility. In this way, we can circle those moments when stock prices plummeted and IV skyrocketed.
- Correlation Heatmap: Put your features (IV, Gamma, PCR, VIX) and target variable (Next_Day_Return) together to see the correlation between them.



