# Manage-Your-Investment-Portfolio-Part-2
This is a part 2 series of elementary finance analysis using Python 

This is a continuation of the part 1 series and hence, we name it as a part 2.

In the part 1, an overview of an investment portfolio is illustrated for a provisional start date (26.04.2021) onwards. The time frequency was set to 2h and a big picture overview was shown. 

In this file, the performance of an investment portfolio is limited (an upper limit but no lower limit) to a maximum number of 21 days with a time frequency of 30 min. If one wants to examine how the portfolio from the part 1 performed for a particular (any time period) number of days or even hours that is possible by implementing the code below.

## Breakdown of the file:

Cell 1 → Different types of modules are imported.

Cell 2 → A start, and an end date are defined together with hours. A connection to the Binance API is created to generate BTC prices.

Cell 3 → Data related to all the transactions that were made (corresponding to the part 1) is generated. 

Cell 4 → Since with this project/code you generate data for a small period of time, which may be within the transaction or after some of them, BTC prices for all the transactions that were made must be generated. Herein, 4 additional DataFrames, including BTC prices for every transaction are created. 

Cell 5 → Data, for instance, BTC owned, USD owned, gain or loss in USD or as a percentage, BTC price to be even, cumulative return of BTC, etc. is generated, corresponding to the transactions. It should be noted that the values for BTC owned are slightly different than in the part 1. This is related to the somewhat different BTC prices that are generated via this approach (API) at the time of the purchase and in general.

Cell 6- 12 → These cells serve as a graphical representation of the above data. For details, see part 1. 
