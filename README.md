# momentum_trading_strategies
An application of high quality and low quality momentum trading on the S&P500, using the IEX Cloud API in Python. 

The high quality and low quality quantitative trading strategies were both built during the course from Nick McCullum as linked: 
https://www.youtube.com/watch?v=xfzGZB4HhEE&list=PL9amRpaUdkPKpjDKwJDoYuIm8Rr4qECLB&index=2&t=6413s&ab_channel=freeCodeCamp.org

After importing a current list of the S&P500 stocks, the one-year price return was used to generate a shortlist of 50 low quality high momentum stocks. Then, given a manual input for the funds in the portfolio, an equal-weighted portfolio with the exact number of shares to purchase was calculated. 

Furthermore, the one-year price return, six-month price return, three-month price return, and one-month price return were all considered to generate a shortlist of 50 high quality momentum stocks. Similar to the low quality strategy, given a manual input for the funds in the portfolio, an equal-weighted portfolio with the exact number of shares to purchase was calculated. Thereafter, the high quality momentum stocks were exported to Excel and reformatted within Python. 
