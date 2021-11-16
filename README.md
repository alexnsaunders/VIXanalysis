This is the start of VIX Analysis

## VIX Analysis

The Cboe Volatility Index (VIX) is created to reflect investors' view of future expected stock market volatility, is often called the market's "fear gauge," and is considered the world's premier barometer of equity market volatility. Some investors use the VIX to measure the level of risk, fear, or stress in the market when making investment decisions. 

Using this index, I will pursue the answer to the following questions:
Q1) Can we use VIX to predict future drops of stock prices, and are there any specific types of recession periods that VIX could foresee more easily? 
Q2) Are there more appropriate industries to use VIX for predicting the future drops? 
Q3) Are there any other appropriate characteristics of companies, such as company size, each company geography (ex. Americas, Europe, and Africa), and each company theme (ex. ESG, Value, Growth, and developed, emerging, and frontier markets), to use VIX for predicting future drops?

Data Sources:
1. Daily VIX data provided by Cboe Global Markets, Inc.: https://www.cboe.com/tradable_products/vix/vix_historical_data/
2. Stock indices data provided by S&P Dow Jones Indices LLC: https://www.spglobal.com/spdji/en/index-finder/

For Q1, we can use the daily VIX data (data sources 1) and the daily S&P 500 index data in the stock indices data (data sources 2). If we calculate the changes in the prices of the S&P 500 index, define the recession periods, and analyze the relationship between the VIX data and the changes in each recession period, we can get the answer for Q1. 

We can analyze it from many aspects, such as the relation between VIX levels and drop levels, the relation between the speed of VIX level change and drop levels, the relation between the total VIX change levels and the total drop levels, and the relation between the correlation of VIX change and drop levels in each recession period and the cause type of the recession, like domestic cause vs. foreign cause. For Q2 and Q3, we can consider the questions from similar aspects. For Q2, we can use the VIX data and the daily S&P 500 index data for each GICS sector in the stock indices data (data sources 2). GICS (The Global Industry Classification Standard) sectors are specific economic sectors that divide companies into 11 sectors that best define their business operations. For Q3, we can use the VIX data, and the daily S&P 500 index data for each company size, each company geography (ex. Americas, Europe, and Africa), and each theme tilted (ex. ESG, Value, Growth, and developed, emerging, and frontier markets) company in the stock indices data (data sources 2).

*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/EDAVtemplate.*	




