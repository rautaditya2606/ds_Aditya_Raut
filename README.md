# Cryptocurrency Trader Performance Analysis by Market Sentiment

## Project Overview

This project examines how cryptocurrency traders perform under different market sentiment conditions. Using historical trade data combined with the Crypto Fear & Greed Index, the goal is to understand how market moods—ranging from Extreme Fear to Extreme Greed—affect trading outcomes, volume, and behavior across different coins and trade sizes.

## Data Used

Two main datasets were analyzed:  

1. **Historical Trade Data:** Includes individual trades with details like execution price, trade size, trade direction, closed PnL, and timestamp.  
2. **Fear & Greed Index Data:** Provides daily sentiment scores and classifications reflecting overall market mood.

## Analysis Approach

The analysis starts by merging trade data with the Fear & Greed Index using trade timestamps. We then calculated key performance metrics, including average Closed PnL and total trading volume, across sentiment categories. The study also looked at how coin types and trade sizes influenced performance in each sentiment scenario.

## Key Findings

- Traders tended to earn the most during periods of **Extreme Greed** and **Fear**, while performance was weaker during **Neutral** and **Extreme Fear** phases.  
- Different coins behaved differently under the same sentiment. For example, PNUT performed exceptionally well during Extreme Fear, while FARTCOIN underperformed. BTC had the highest trading volume overall, with its best PnL occurring during Fear.  
- Larger trades generally resulted in higher average profits. This effect was most noticeable in Extreme Greed and Fear markets, indicating that size and sentiment together can influence returns.

## Insights and Next Steps

- Traders could adjust activity and position sizes depending on market sentiment, increasing exposure during Fear and Extreme Greed while being more cautious during Neutral and Extreme Fear.  
- Building a sentiment-based watchlist of coins can help identify assets that historically perform well (or poorly) under certain market conditions.  
- Additional analysis could explore the effect of execution price and leverage on performance, and statistical tests could be conducted to confirm the significance of these patterns.

This study provides a foundation for understanding how market sentiment, coin selection, and trade size interact, offering actionable insights for smarter trading strategies in the crypto market.
