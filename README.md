# pairs-trading

Pairs Trading (Mean Reversion) strategy.
Fundamental logic is we find a pair of stocks that historically follow each other closely. We can use historical mean data to go long or short when the prices diverge more than the historical mean.

1. First I did analysis by grouping stocks from the S&P500 into 3 sectors (Tech, Healthcare, Energy).
2. Decided to go with Energy and found a suitable pair with high correlation and cointegration values.
