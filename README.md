


**Features**

1. Computes expected returns from historical price data

2. Calculates annualized volatility and asset correlations

3. Constructs the Efficient Frontier using MPT principles




**Optimizes for**

1. Maximum Sharpe Ratio

2. Minimum Volatility

3. Target return or target risk portfolios


Visualizes portfolio allocations and risk-return tradeoffs
Clean modular code with reusable functions

Libraries Used

1. PyPortfolioOpt – portfolio optimization logic

2. pandas – data handling

3. numpy – numerical operations

4. matplotlib – plotting and visualizations

5. yfinance – for pulling historical asset prices

**What it does**

1. Clean & preprocess – The script computes daily returns and filters missing data.

2. Estimate parameters – Expected returns and covariance matrix using historical data.

3. Optimize portfolio – With PyPortfolioOpt’s EfficientFrontier class:

4. Maximize Sharpe Ratio (risk-adjusted return)

5. Minimize volatility

6. Optimize for a specific target return






