# SP500-tracking-highlow
Keep track of the stock market's volatility.


The High-Low Gap indicates the security's price range and is a useful measure of stock price volatility.

The Python script determines whether the High-Low gap of an S&P500 company's stock today (at the time the script is executed) is greater than the 10-day average of that gap.

The csv file for S&P500 firms may be found at https://datahub.io/core/s-and-p-500-companies-financials#resource-s-and-p-500-companies-financials zip.



The result is an Excel file including the companies that meet the above criteria, as well as their market history for the current date's High, Low, Volume, and the average of Volume and High-Low gap in the previous 10 days.



The following packages were used: pandas, numpy, yfinance, and datetime.