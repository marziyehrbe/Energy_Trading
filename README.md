# Energy_Trading

One of your colleagues have developed a quite profitable trading strategy. The strategy works by opening a position on the spot (day-ahead) market,
and then close the position on the intraday market. It’s however starting to decline in performance, so you’re tasked with coming up with a new strategy.
You have been given a file (data_for_exercise.csv), that contains the following columns.

data_input.columns = [ts, wind, solar, cons, spot, market]
ts: Timestamp [-]
wind, solar, cons: Forecasted wind, solar and consumption [MW]
spot: The spot price we’re able to open the positions at on [EUR/MWh]
market: The intraday price we’re able to close the positions at [EUR/MWh]
To compare the two strategies, build a trading strategy on the provided data and propose appropriate metrics to evaluate the strategies. Preferable supported by visualization.
