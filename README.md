This is a project that I made for the interview round for a data science internship at OptAlpha.

Here, I have executed the following problem statement:

Assignment: Analysis of Candlestick Data using Unsupervised Learning like
Clustering
Objective: Application of unsupervised learning techniques to identify clusters on
candlestick data and extract insights for trading decisions. Identified clusters shall represent
some candlestick chart patterns and/or price action patterns which can be utilised to make
better trading decisions.
Dataset: We will provide you with a dataset of 1-minute level candlestick data. You can
start with a small sample of recent few months if the dataset is too large for you to handle.
Tasks:
1. Data Pre-processing: Load the dataset and perform any necessary pre-processing
(Like Normalization of the data)
2. Feature Engineering: Create relevant features from the candlestick data (Hint: take
data from past 30 or 60 candles)
3. Clustering:
a. Apply a clustering algorithm to identify patterns or clusters.
b. Determine the optimal number of clusters.
4. Cluster Analysis and Insights: Analyse each cluster to identify common characteristics
(patterns, trends, correlations)
5. Trading Insights:
a. Summarize the key insights gained from the clustering analysis. Explain how
the identified clusters can be used to inform trading decisions and strategies.
(Hint: check if price moves up/down in next 5 minutes)
b. Provide recommendations on how the insights from this analysis can be
leveraged to improve trading performance or develop new trading
approaches.
c. Identify examples, such as price movements and target percentages.



From the project, I found the ideal number of clusters to be 2 and from this, I have identified various recommendations for traders by taking note from the observations .
Two such observations maybe:
1.In this cluster there is a pattern where prices tend to fall over the first 5 minutes, consider taking a long position when data points fall into this cluster. When the prices increase over the first minutes , consider taking the short position.
2.Avoid trading during periods identified as high volatility clusters unless your strategy is designed to handle such volatility. Use stop-loss orders aligned with historical price movements within each cluster to mitigate risks.
