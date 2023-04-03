# Google Trends Bond Futures Modeling

## Introduction - 4/3/23 

For speed, I will scriptkiddye Ming/Fong/Datadunce's existing code to prelim test Momo AND MeanRev trading strats for US Treasury Futures 
based on Google Trend data for certain selected keywords. After general delta 1 move backtests on daily closes, will implement Relative Value Aspects

## Alternative Data- 4/3/23 
Google Trends search volume data = punting US Treasury Futures or index/crypto/equity/future.

As retail, tough to pay $$ for granular Time and Sales numbers... so prelim daily historicals from [yfinance](https://pypi.org/project/yfinance/) for now.

Will work on mashing /Datadunce 's barchart code later (https://gist.github.com/cf7ad12df1a3d74fd8fee28e16639419.git).

TrendData is downloaded through the [Pytrends](https://pypi.org/project/pytrends/) module using the Google Trends API.

## Rudimentary BackTesting
Backtesting is done using the [Backtesting.py](https://kernc.github.io/backtesting.py/) package

## Beginning Hypothesis of Results - 4/3/23

High-Level Personal Bias: Daily close historicals not enough to run real money. Need Extended Hours 1min + Reg Hours 1min + ICE Exchange Interest Rate Swap 1min Data 
Momo Bias - Will be undwhelming 2015 - 2017 and will work in spurts correlated to recent fed hiking cycle
MeanRev Bias - promising enough for me to waste time on this


## Resources
Papers: https://www.researchgate.net/publication/326503702_Algorithmic_Trading_Systems_Based_on_Google_Trends
https://jackdry.com/predicting-realized-volatility-using-google-trends
Datadunce Barchart 1min code - (https://gist.github.com/cf7ad12df1a3d74fd8fee28e16639419.git)
https://pypi.org/project/yahoofinancials/ 

## Credit For beginning equityindex code - Ming Fong and Alexander Yang 
## Future Credit to Datadunce if I get around to Barchart 1min implementation
