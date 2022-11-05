# Bitcoin Financial Data Exploration

## Dataset

The data consisted of historical daily market data of Bitcoin from 2013 - 2019. The original dataset contained the historical market data of the top ten cryptocurrencies from 2013 - 2019. I had to cut out only the Bitcoin data for the purpose of my investigation. No duplicate records and zero price points were removed (if any) . The dataset was downloaded from [Kaggle](https://www.kaggle.com/datasets/philmohun/cryptocurrency-financial-data).


## Summary of Findings

In my findings, **the price of Bitcoin perform better overall over the years**. However, looking at it short term performance(every 3 months), there are multiple ups and downs and they are hard to predict or measure. Also, it will interest you to note that in every upward movements there is a downward spiral that follows (vis-a-vis), although it will be hard to figure if the next move will be up or down and when it will happen.

Beyond price, experience Crypto Investors use **market cap** to tell a more complete story and compare value across cryptocurrencies. As a key statistic, it can indicate the growth potential of a cryptocurrency and whether it is safe to buy, compared to others. In my findings, the market play impacted price of Bitcoin and volume. As the market cap increase, the price also increases over the years.

Also, the more people buy and sell bitcoin, the price tend to increase. However, if there more people are selling their Bitcoin, the price will eventually go down and may result to a crash.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the four variable of bitcoins. I start by introducing the
price variable using Histplots, followed by the market_cap, and then plot the volume also using a KDE to understand the distribution. The values for the market cap were large so I had to define a scale.

Afterwards, I check the relationship of my four variables of interest mostly in pairs(two). I use multiple visualization tools like regplot and heatmaps to check for the relationship that exist between the price, marketcap, and volume. Last I also used lineplot to check for the any posiblity of influence between the price and categorical variables like quarter and month_index. I've made
sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.

Disclaimer: This is not an investment advice or solication to buy Bitcoin or any other crypto assets. This report was done only for educational purposes# communicate-data-findings
