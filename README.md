# Automated Stock Trading using Deep Reinforcement Algorithms

Design an automated trading solution for single stock trading using an  ensemble strategy that employs deep
reinforcement schemes.

### Phase I: Financial Data Processing and Technical Indicators

1. Download Dow-30, NASDAQ-100, or S&P 500 data, including Open, High, Low, Close prices, and Volume (OHLCV) and fundamental indicators.

2. Obtain technical indicators and perform feature engineering: technical indicators, such as MACD, RSI; and fundamental indicators, such as EPS, ROI, ROE, P/E, P/S.

### Phase II: Stock Selection and Portfolio Allocation with Backtesting Results

1. Stock Selection: Perform supervised machine learning using classic machine learning algorithms (LSTM, Random Forest, SVM, Linear Regression, Lasso, Ridge) to select stocks based on fundamental multi-factor data, and select the top 25% of stocks every quarter; 

2. Portfolio Allocation: Use DRL Ensemble strategy (including PPO, DDPG, A2C, SAC, and TD3) in FinRL for asset allocation of the selected stocks, trade with daily data, and output positions

### Phase III: Deploy a DRL agent to an online trading platform

1. Deployment: Deploy strategies to online trading platforms such as Alpaca for paper trading

