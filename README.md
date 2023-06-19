# BTCTrendline
# Data source: https://www.kaggle.com/datasets/tencars/392-crypto-currency-pairs-at-minute-resolution
# Platform: Kaggle
# Strategy intro: 
Object: BTCUSD
Time: every minite from 2017
Intro:
Trends can be identified by  signal processing methods.
By using some filtering methods in signal processing theory, the drawbacks of MA indicators can be overcome by new constructed low latency trend (LLT).
By forward differential calculation, we can get the slope of the LLT trend line tangent at the end of each trading period. 
If the slope is greater than zero, go long, and if the slope is less than zero, go short.
