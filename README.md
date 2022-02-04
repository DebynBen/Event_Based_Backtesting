# Event_Based_Backtesting
Backtest three diffrent trading strategies SMA Cross, Momentum, and Mean reversion strategies.  

There are two other strategies that can be used to execute trades which are long only & long-short. This program contains a base file know as backtest_base.py. Which will retrieve and prepare data, helper/convenience functions, place orders, and close out trades. Both the long only & long-short classes inherant from backtest_base.py. Operation is simple, choose to run backtest_long_only.py or backtest_long_short.py and performance information will be printed in the terminal.

* Note if using Bitstamp data the price action is too volitaile and doesn't work well for this strategy. Please make sure to update backtest_base.py, with the AUDUSD=X.csv to see a better representation of this particular strategy.
