  /$$$$$$                                  /$$               /$$$$$$                          /$$       /$$   /$$    
 /$$__  $$                                | $$              /$$__  $$                        | $$      |__/  | $$    
| $$  \ $$ /$$   /$$  /$$$$$$  /$$$$$$$  /$$$$$$   /$$$$$$$| $$  \__/  /$$$$$$  /$$$$$$/$$$$ | $$$$$$$  /$$ /$$$$$$  
| $$  | $$| $$  | $$ |____  $$| $$__  $$|_  $$_/  /$$_____/| $$ /$$$$ |____  $$| $$_  $$_  $$| $$__  $$| $$|_  $$_/  
| $$  | $$| $$  | $$  /$$$$$$$| $$  \ $$  | $$   |  $$$$$$ | $$|_  $$  /$$$$$$$| $$ \ $$ \ $$| $$  \ $$| $$  | $$    
| $$/$$ $$| $$  | $$ /$$__  $$| $$  | $$  | $$ /$$\____  $$| $$  \ $$ /$$__  $$| $$ | $$ | $$| $$  | $$| $$  | $$ /$$
|  $$$$$$/|  $$$$$$/|  $$$$$$$| $$  | $$  |  $$$$//$$$$$$$/|  $$$$$$/|  $$$$$$$| $$ | $$ | $$| $$$$$$$/| $$  |  $$$$/
 \____ $$$ \______/  \_______/|__/  |__/   \___/ |_______/  \______/  \_______/|__/ |__/ |__/|_______/ |__/   \___/  
      \__/                                                                                                          

#[Fianchetto](https://www.tradingview.com/script/vCEoFf0a-Fianchetto-v1/)
  - Language = PineScript for use with [TradingView](www.TradingView.com)
  - Trend Strategy
  - High Frequency of Signals
  - Long and Short
  - 200 Day Moving Average for trend
  - 7 Day Moving Average for signals
    - BUY = When 7 Day MA > 200 Day MA, AND 7 Day MA Direction is up with a 0.7 volume factor
    - SELL = When 7 Day MA < 200 Day MA, AND 7 Day MA Direction is down with a 0.7 volume factor
    
The idea behind Fianchetto was to utilize the direction of a Moving Average to gain an alpha over Standard Moving Average 
crossover strategies. while using larger Moving Average to filter out trading against the trend only allowing longs, or 
only shorts. We also gain an edge by using a Volatility factor to the Moving Average filtering out white noise throughout
the trade. 
