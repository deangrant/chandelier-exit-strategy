# Chandelier Exit

Chandelier Exit (CE) is a volatility-based indicator that identifies stop loss exit points for long and short trading positions.

Chandelier Exit is based on the Average True Range (ATR) indicator. It is designed to keep traders in the trend until a defined trend reversal happens. Traders use CE to maximize their returns in a trade and make stop loss exit decisions. It is based on the principle that a trend reversal is highly probable when the price of an asset moves against an existing trend up to three times the average volatility. It uses the high and low prices over a defined period of time to compute the CE value.

## How to Use Chandelier Exit

The main objective of using Chandelier Exit is to alert the trader to a possible trend reversal after an extended trend. During lower volatility trading sessions, traders set small trailing stop losses. This allows them to close their trades near the top and get maximum returns on their investments. The possibility of a trend reversal is low during low volatility trading sessions. However, in higher volatility trading, traders set a larger trailing loss in order to protect themselves from choppy trading.

Due to the close relationship between stop loss and volatility, traders use Chandelier Exit as a trailing stop-loss and as a way of protecting themselves from losses resulting from trend reversals. Most professional traders recommend using Chandelier Exit as a stop loss tool rather than as a tool for generating trading signals. This is because as a trading signal it is prone to generating false signals.

When using Chandelier Exit for technical analysis, Charles Le Beau recommended setting an input period of 22 and a multiple of 3 times the Average True Range. The reason for using an input period of 22 is that there are usually 22 trading days in a month. Using 22 price levels allows for short-term fluctuations in price. However, experienced traders have the freedom to choose different settings depending on their risk tolerance and trading style.

## Formula and Calculations

Chandelier Exits show two lines – the chandelier exit long and the chandelier exit short. The exit long is used to close long positions whereas the exit short is used to close short positions. Therefore, the rule of the indicator is to close long positions when the price goes below the exit long and to close short positions when the price goes above exit short.

The Chandelier long and short are used to compute the value of ATR. Then, using the recommended setting of 22 periods, the Chandelier exit will calculate the highest high or the lowest low for the same period used to calculate ATR. Lastly, subtract the multiple ATR from the figure obtained for the highest high, and add multiple ATR to the value obtained for the lowest low.

The formulas for the two lines are as follows:

Chandelier Exit Long: n-day Highest High – ATR (n) x Multiplier

Chandelier Exit Short: n-day Lowest Low + ATR (n) x Multiplier

Where:

N is the default unit period of 22 or the number that the trader chooses.
The multiplier is the default 3.0 Average True Range