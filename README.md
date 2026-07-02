# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and historical trader performance. By combining market sentiment data with trading records, the project investigates how different market conditions influence trading profitability, trading behavior, and overall performance.

---

## Objectives

- Understand and explore both datasets.
- Perform data cleaning and preprocessing.
- Engineer meaningful features for analysis.
- Conduct Exploratory Data Analysis (EDA).
- Perform statistical analysis to validate findings.
- Generate business insights and recommendations.

---

## Datasets

### 1. Fear & Greed Index Dataset
- Daily market sentiment values.
- Sentiment categories:
  - Extreme Fear
  - Fear
  - Neutral
  - Greed
  - Extreme Greed

### 2. Historical Trading Dataset
- Account
- Coin
- Execution Price
- Size USD
- Side
- Closed PnL
- Fee
- Timestamp
- Transaction Details

---

## Project Workflow

### Phase 1: Data Understanding
- Dataset dimensions
- Data types
- Missing value analysis
- Duplicate detection
- Summary statistics
- Data quality assessment

### Phase 2: Data Cleaning
- Duplicate removal
- Missing value handling
- Date conversion
- Numeric type conversion
- Outlier investigation

### Phase 3: Feature Engineering
- Trading Date
- Day of Week
- Profit/Loss Flag
- Trade Size Category
- Profit Percentage
- Daily Trader PnL
- Daily Trade Count

### Phase 4: Exploratory Data Analysis
- Market Sentiment Distribution
- Daily Sentiment Trend
- Closed PnL Distribution
- Average Profit by Sentiment
- Win Rate by Sentiment
- Buy vs Sell Analysis
- Coin-wise Profitability
- Top Profitable Coins
- Top Traders
- Top Losing Traders
- Trade Size vs Closed PnL
- Fee vs Closed PnL
- Daily Trading Activity
- Correlation Heatmap
- Box Plot
- Violin Plot

### Phase 5: Statistical Analysis
- Independent T-Test
- One-Way ANOVA
- Correlation Analysis
- Median Profit Analysis
- Profitability Rate
- 95% Confidence Interval

### Phase 6: Business Insights & Recommendations

### Phase 7: Limitations

### Phase 8: Future Work

### Phase 9: Conclusion

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## Repository Structure

```
bitcoin-market-sentiment-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── images/
│
├── notebooks/
│
├── report/
│
├── README.md
└── requirements.txt
```

---

## Key Findings

- Market sentiment has a measurable impact on trader profitability.
- Extreme Greed showed the highest percentage of profitable trades.
- Trade size has only a weak positive correlation with profit.
- Trading profits are concentrated among a small number of traders and cryptocurrencies.
- Statistical tests confirmed significant differences in profitability across market sentiment categories.

---

## Future Improvements

- Build machine learning models to predict trading profitability.
- Include additional market indicators such as Bitcoin price, volatility, and trading volume.
- Develop an interactive dashboard using Power BI or Tableau.
- Perform real-time sentiment analysis using live cryptocurrency data.

---

## Author

**Sakshi Tambe**

Aspiring Data Analyst | Data Science & Machine Learning Enthusiast

- Python
- SQL
- Data Analysis
- Machine Learning
- Power BI