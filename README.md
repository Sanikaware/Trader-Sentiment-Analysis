# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear/Greed) affects trader behavior and profitability using Hyperliquid trading data.

---

## Project Structure

```text
data/       -> datasets
notebook/   -> Jupyter notebook
charts/     -> exported charts
```

---

## Features
- Data cleaning and preprocessing
- Sentiment analysis
- Trader segmentation
- PnL analysis
- Visualization
- Predictive ML model using Random Forest

---

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Open notebook:

```bash
jupyter notebook
```


Run:
`Trader_Performance_Sentiment.ipynb`

---

## Key Insights
- Fear periods showed lower trader profitability.
- High leverage traders experienced larger PnL volatility.
- Sentiment contributed useful predictive signals.

---

## Strategy Recommendations
- Reduce leverage during Fear periods.
- Avoid excessive trading during extreme Greed conditions.