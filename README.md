# BTC-time-series
**BTC-USD data set for price regression**

Key points:
- BTC time series data resampled to 10 min granularity
- Format: Time Opening High Low Close Volume
- Use the last 10,000 points for an initial model (2.5 months)
- Use first 8,000 steps for training, and then 1,000 for testing, and 1,000 for validation
- Original data avilable from https://api.bitcoincharts.com/v1/csv/ in the bitstampUSD.csv.gz datta set.

***
Potentially useful:
- http://cs229.stanford.edu/proj2014/Isaac%20Madan,%20Shaurya%20Saluja,%20Aojia%20Zhao,Automated%20Bitcoin%20Trading%20via%20Machine%20Learning%20Algorithms.pdf

