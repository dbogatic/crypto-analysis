# Crypto Analysis
![image](images/cryptocurrency.jpg)

* This repo attempts to determine the direction of crypto asset movement based on selected market information as well as to identify if there are leading indicators that could point the direction of movement.

* Data obtained from [Coinmetrics](https://docs.coinmetrics.io/api/v4) community (free) level API.
#
## Data Analyzed

* Velocity (VelCur1yr) - The ratio of the value transferred (i.e., the aggregate "size" of all transfers) in the trailing 1 year divided by the current supply on that day. It can be thought of as a rate of turnover -- the number of times that an average native unit has been transferred in the past 1 year.

* Network Value to Transaction (NVTAdj) - The ratio of the network value (or market capitalization, current supply) divided by the adjusted transfer value. Also referred to as NVT.

* Transaction Count (TxCnt) - The sum count of transactions that day. 

* Transaction Volume (TxTfrValAdjUSD) - The USD value of the sum of native units transferred that day removing noise and certain artifacts.

* Exponential Moving Average (EMA) - Technical analysis to determine price movement compared to its average as well as crossing points that could point to trend reversal.

* Hash Rate, Mean (HashRate) - Hash rate is derived from difficulty (DiffMean), the rate at which block came in (BlkIntMean) and depending on the protocols, some other pieces of data. It gives an estimate of how much hash power is mining a given chain.

* Additionally, I compared BTC and ETH with main market indexes S&P 500, Dow Jones Industrial Average and Nasdaq-100 to determine cumulative return, volatility, Sharpe and Sortino ratios. 

* Added backtesting SMA strategy for BTC and ETH using [Vectorbt](https://github.com/polakowo/vectorbt) API.

* Index data pulled using [yfinance](https://pypi.org/project/yfinance/) API. 

#
© 2021 Author: Dragan Bogatic