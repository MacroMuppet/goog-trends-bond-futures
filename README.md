# Google Trends Bond Futures Modeling
## Credit For beginning equityindex code - Ming Fong and Alexander Yang 

## Introduction - 4/3/23 

For speed, I will script_kiddy massage Ming/Fong/Datadunce's existing code to prelim test Momo AND MeanRev trading strats for US Treasury Futures 
based on Google Trend data for certain selected keywords.

##Alternative Data- 4/3/23 
Google Trends search volume data = punting US Treasury Futures or index/crypto/equity/future.

As retail, tough to pay $$ for granular Time and Sales numbers... so prelim daily historicals from [yfinance](https://pypi.org/project/yfinance/) for now.

Will work on mashing /Datadunce 's barchart code later (https://gist.github.com/cf7ad12df1a3d74fd8fee28e16639419.git).

TrendData is downloaded through the [Pytrends](https://pypi.org/project/pytrends/) module using the Google Trends API.

##Rudimentary BackTesting
Backtesting is done using the [Backtesting.py](https://kernc.github.io/backtesting.py/) package

##Beginning Hypothesis of Results 4/3/23
- Daily close historicals not enough to run real money. Need Extended Hours 1min + Reg Hours 1min + ICE Exchange Interest Rate Swap 1min Data 




## Resources
Papers: https://www.researchgate.net/publication/326503702_Algorithmic_Trading_Systems_Based_on_Google_Trends
https://jackdry.com/predicting-realized-volatility-using-google-trends

#Future Credit to Datadunce if I get around to Barchart 1min implementation
