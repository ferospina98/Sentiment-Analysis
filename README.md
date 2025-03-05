# Sentiment-Analysis

This project analyzes the impact of recession fears and media sentiment on S&P 500 stock market movements. By leveraging Python, machine learning, and financial market data, this analysis aims to uncover correlations between news sentiment and stock price fluctuations.

1. Technologies used
- Python: pandas, NumPy, scikit-learn, matplotlib, seaborn
- Natural Language Processing (NLP): Sentiment analysis on financial news
- Machine Learning: Regression models to predict stock movements
- Data Visualization: Matplotlib and seaborn for graphical insights
- Jupyter Notebook: For exploratory data analysis (EDA)
- Web Scraping/APIs: Extracting financial news data

2. Key Findings
- Sentiment Polarity and Subjectivity Impact:
  - While sentiment polarity and subjectivity had some influence, their correlation with SPY closing prices was relatively weak (around 0.14).
  - This suggests that sentiment alone is not a strong predictor of market movements.

- Historical Prices as the Strongest Predictor:
  - The most significant feature in the model was the previous day’s SPY closing price (Close_SPY_lag_1), indicating that historical stock prices are far more predictive of future prices than sentiment metrics.
  - This aligns with the efficient market hypothesis, which suggests that stock prices already reflect all available information.

- Random Forest Model Performance:
  - After hyperparameter tuning, our Random Forest model achieved an R² of ~0.99, showing that the model accurately predicts SPY closing prices but primarily based on historical prices, rather than sentiment factors.

