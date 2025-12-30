Trader Behavior Insights: Market Sentiment Analysis
•	Problem Statement
•	This project analyzes the relationship between Bitcoin market sentiment (Fear vs Greed) and trader behavior using historical trading data from Hyperliquid. The objective is to uncover how sentiment impacts trader performance, risk-taking, and decision-making, and to derive insights that can inform smarter trading strategies.
•	Datasets Used
•	1. Bitcoin Fear & Greed Index:
   - Columns: date, classification (Fear, Greed)

2. Hyperliquid Historical Trader Data:
   - Columns include Account, Coin, Execution Price, Size USD, Side, Timestamp IST, Closed PnL, Fee, etc.
•	Methodology
-	Cleaned and preprocessed both datasets
- Converted timestamps to date format
- Merged trading data with market sentiment using date
- Performed exploratory data analysis (EDA)
- Conducted statistical testing to compare trader performance
- Segmented traders based on profitability
- Visualized patterns using charts and graphs
•	Key Analysis Performed
-	Comparison of average PnL during Fear vs Greed periods
- Trade size behavior under different sentiment regimes
- Buy vs Sell performance analysis
- Daily PnL trends based on market sentiment
- Identification of consistent winning and losing traders
•	Key Findings
-	Traders tend to achieve higher average profits during Greed periods, but with increased volatility
- Fear periods show reduced trade sizes, indicating cautious behavior
- Buy-side trades generally perform better during Greed phases
- A small subset of traders consistently remains profitable across both sentiment regimes
- Statistical testing indicates a significant difference in trader performance between Fear and Greed periods
•	Trading Strategy Implications
-	Reduce position sizes and manage leverage during Greed phases to limit downside risk
- Adopt conservative and selective strategies during Fear periods
- Integrate sentiment indicators into risk management systems
- Monitor trader behavior to identify high-risk patterns during extreme market sentiment
•	Tools & Technologies
-	Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy
- Jupyter Notebook
•	Future Enhancements
-	Incorporate leverage data more deeply into risk analysis
- Apply machine learning models to predict trader performance
- Extend analysis to additional market indicators
- Build real-time sentiment-aware trading dashboards
