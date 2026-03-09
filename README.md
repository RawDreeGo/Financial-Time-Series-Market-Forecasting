# Financial Time-Series & Market Forecasting

## 🎯 Project Overview
This project provides a quantitative analysis pipeline built to extract, clean, and forecast financial asset prices. By leveraging Autoregressive (AR) models and statistical stationarity tests, this project transforms historical market volatility into a 20-day predictive roadmap with 90% confidence intervals, enabling data-driven investment decision-making.

## 🚀 Key Milestones

1. **Data Engineering & Pipeline:** Developed an automated pipeline for historical financial data extraction. This stage included robust data cleaning, handling non-trading days (market holidays), and ensuring dataset integrity for comparative analysis.
2. **Statistical Stationarity Analysis:** Performed Augmented Dickey-Fuller (ADF) tests to confirm data stationarity. This critical preprocessing step ensures the model captures genuine price momentum rather than random market noise.
3. **Model Architecture (AR):** Implemented an optimized Autoregressive (AR) model. I performed careful lag (p) selection to minimize prediction error and accurately reflect temporal dependencies in asset pricing.
4. **Forecasting & Probability Mapping:** Generated a 20-day price projection complemented by a 90% confidence interval. This visualization provides a probabilistic roadmap, crucial for assessing market risk and upside potential.

## 🛠 Tech Stack
* **Python:** Core language for data analysis and modeling.
* **Pandas & NumPy:** For time-series structuring and numerical computation.
* **Statsmodels:** Utilized for statistical testing and AR model implementation.
* **Matplotlib:** Advanced visualization of time-series data, forecast trends, and confidence intervals.

## 📊 Key Results

<img width="997" height="530" alt="binance 02" src="https://github.com/user-attachments/assets/4f0082b2-8ac3-44e9-9766-39d84b67e745" />

*The final model’s projection successfully captured market trends, providing stakeholders with a quantitative baseline for future price movement assessment.*

## 📈 Conclusion
This project demonstrates the ability to convert complex, real-world financial data into actionable insights. By combining rigorous statistical validation with predictive modeling, the analysis bridges the gap between historical performance and future strategy.
