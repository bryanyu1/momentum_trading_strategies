# momentum_trading_strategies
An application of high quality and low quality momentum trading on the S&P500, using the IEX Cloud API in Python. By definition, high quality momentum stocks show "slow and steady" outperformance over long periods of time, whereas low quality momentum stocks might not show any momentum for a long time, and then surge upwards. 

The high quality and low quality quantitative trading strategies were both built, using the course from Nick McCullum: 
https://www.freecodecamp.org/news/algorithmic-trading-using-python-course/

After importing a current list of the S&P500 stocks, the one-year price return was used to generate a shortlist of the top 50 low quality momentum stocks. Then, given a manual input for the funds in the portfolio, an equal-weighted portfolio with the exact number of shares to purchase was calculated. 

Furthermore, the one-year price return, six-month price return, three-month price return, and one-month price return were all considered to generate a shortlist of the top 50 high quality momentum stocks. Similar to the low quality strategy, given a manual input for the funds in the portfolio, an equal-weighted portfolio with the exact number of shares to purchase was calculated. Thereafter, the high quality momentum stocks were reformatted in Python and exported to Excel. 
