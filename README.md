# Pairs-Trading-Model-Using-Quantopian
My team and I analyzed the S&p 500 in conjunction with the NASDAQ 100.  To do this we examined the moving average crossover using z-scores for daily percent change. 
We then calculated the 7 day moving average of closing prices and z-scores of the daily percent change. If moving averages crossover eachother, this usually indicates a change change in trend.  If the z-scores are above or below 1.5 standard deviations this indicates a sharp change in price from the previous day which indicates the beginning of an upward trend or downward trend.

Quantopian's IDE was used to run this, so the code can only be run in Quantopian's IDE. 

Performance Metrics: 
  
  Sharpe Ratio: .79

  Alpha: .07

  Total Returns: 230.24%

  Beta: .64
