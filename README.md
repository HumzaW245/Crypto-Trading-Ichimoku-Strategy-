# Crypto-Trading-Ichimoku-Strategy-
A trading bot that scans USDT pairs on Binance and returns a list of coins meeting the strategy's conditions on a given time frame.

v0.01
Currently this version uses ichimoku with the following conditions:
1) Lagging span (Chikou) is above its cloud (Kumo)
2) Current price close is above its cloud (Kumo)
3) Tenkan (Conversion line) is above Kijun (Base line)
4) Projected cloud (Kumo) is a green cloud.

The code also updates a excel file which was used to test accuracy. The main functionality of this code is testing the above Ichimoku strategy.

Testing was done in a downtrending market and the strategy was only looking for LONG positions so accuracy suffered. Will look to test more in the future but v0.02 will be worked on to see if Ichimoku conditions need to be changed for improvement.
