Trader Behavior Insights: Market Sentiment Analysis
Problem Statement
This project analyzes the relationship between Bitcoin market sentiment (Fear vs Greed) and trader behavior using historical trading data from Hyperliquid. The objective is to uncover how sentiment impacts trader performance, risk-taking, and decision-making, and to derive insights that can inform smarter trading strategies.
Datasets Used
1. Bitcoin Fear & Greed Index:
    Columns: date, classification (Fear, Greed)

2. Hyperliquid Historical Trader Data:
    Columns include Account, Coin, Execution Price, Size USD, Side, Timestamp IST, Closed PnL, Fee, etc.

Methodology
Cleaned and preprocessed both datasets
 Converted timestamps to date format
 Merged trading data with market sentiment using date
 Performed exploratory data analysis (EDA)
 Conducted statistical testing to compare trader performance
 Segmented traders based on profitability
 Visualized patterns using charts and graphs
 
Key Analysis Performed
Comparison of average PnL during Fear vs Greed periods
 Trade size behavior under different sentiment regimes
 Buy vs Sell performance analysis
 Daily PnL trends based on market sentiment
 Identification of consistent winning and losing traders
 <img width="1043" height="507" alt="Daily Trader PnL vs Market Sentiment" src="https://github.com/user-attachments/assets/74bca322-a8a1-4725-a3a4-76e187e0654a" />
<img width="850" height="547" alt="Win Rate b Market Sentiment and Trade Direction" src="https://github.com/user-attachments/assets/6e15a095-ca5b-4c32-b777-49746b4a9768" />
<img width="733" height="470" alt="Trader PnL Distribution Fear vs Greed" src="https://github.com/user-attachments/assets/621b069e-0a2b-4757-83d6-b4b6d2bbf7f8" />
<img width="704" height="470" alt="Average Trade Size by Market Sentiment" src="https://github.com/user-attachments/assets/624a8a1a-fe3a-4994-9006-33a888c1da46" />
<img width="686" height="470" alt="PnLb Trade Direction   Market Sentiment" src="https://github.com/user-attachments/assets/8ec23d71-7ee1-4847-bcfa-8703a4caac63" />


Key Findings
Traders tend to achieve higher average profits during Greed periods, but with increased volatility
 Fear periods show reduced trade sizes, indicating cautious behavior
 Buy-side trades generally perform better during Greed phases
 A small subset of traders consistently remains profitable across both sentiment regimes
 Statistical testing indicates a significant difference in trader performance between Fear and Greed periods

Trading Strategy Implications
Reduce position sizes and manage leverage during Greed phases to limit downside risk
 Adopt conservative and selective strategies during Fear periods
 Integrate sentiment indicators into risk management systems
 Monitor trader behavior to identify high-risk patterns during extreme market sentiment


Tools & Technologies
Python
 Pandas, NumPy
 Matplotlib, Seaborn
 SciPy
 Jupyter Notebook

Future Enhancements

Incorporate leverage data more deeply into risk analysis
 Apply machine learning models to predict trader performance
 Extend analysis to additional market indicators
 Build real-time sentiment-aware trading dashboards
