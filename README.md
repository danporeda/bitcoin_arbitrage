# bitcoin_arbitrage #

This app is a process of data analysis comparing Bitcoin price indexes between Bitstamp and Coinbase during the Q1 period of 2018. The data is collected from CSV files, prepared, and analyzed. The final analysis reveals where arbitrage opportunities exist throughout the 2018 Q1 time period.
---
## Final analysis

Three dates were selected in comparative Bitcoin exchanges (Bitstamp and Coinbase) during the first quarter of 2018: (early)2018/01/27, (middle)2018/02/15, and (late)2018/03/31. For each date, a dataframe containing the Timestamps and closing prices were created from both indexes (Bitstamp and Coinbase). The spread between both indexes was determined by calculating the difference between closing prices on comparative Timestamps. These spreads were further filtered to those >1% to account for the 1% trading fees. There was considerable profit potential on the early date, but 0 profitable trades on the selected middle and late dates. based on this selection, the arbitrage opportunities changed significantly over the course of 2018 Q1, from significant profit potential on the early portion of the quarter, to scarce arbitrage opportunites in the later portion of the quarter.

