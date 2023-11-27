# MomentumFactor in Crypto Top 50
 This is a backtest for single Momentum Factor in Top 50 Cryptos

 The replication of the cross-sectional single-factor momentum strategy on the Top 50 market cap cryptocurrencies: The momentum factor reflects the continuation of relative strength trends between stocks, following the principle of 'the strong get stronger, and the weak get weaker.' This is typically achieved by longing the stocks with the best performance over a certain period (referred to as the winner portfolio) and simultaneously shorting the stocks with the worst performance over that period (referred to as the loser portfolio) to construct the momentum factor.

In the construction process, I primarily use a 20-day momentum calculation. The code includes aspects such as long-short backtesting (including Sharpe ratio, Calmar ratio, maximum drawdown, average drawdown recovery time, etc.) and the calculation of information ratios such as IC and IR.

For data, I obtained it through the API of the Binance exchange and stored it in a database. Stablecoins pegged to USD were excluded from the assets. The entire backtesting process was implemented using Pandas and Numpy.
