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
#
© 2021 Author: Dragan Bogatic