# Silver Price Forecasting & Market Trend Analysis (2016–2026)

##  Project Overview

Predicting commodity prices is a cornerstone of strategic financial planning and risk management. This project focuses on the **quantitative analysis and forecasting of Silver prices**, spanning a decade from 2016 to 2026. By utilizing historical data and advanced predictive modeling, this study identifies long-term bullish trends and price volatility boundaries.

As a **Business and Data Analyst**, I processed over 2,500 daily records to build a robust forecasting model that provides actionable insights for investors, industrial manufacturers (electronics/solar), and financial institutions looking to hedge against inflation.

---

##  Business Objectives

The analysis serves several critical business functions:

1. **Investment Strategy:** Identifying long-term price trajectories to assist in portfolio diversification.
2. **Procurement Optimization:** Helping industrial stakeholders anticipate future cost increases in silver-reliant supply chains.
3. **Risk Mitigation:** Utilizing confidence intervals (Upper/Lower bounds) to assess potential market volatility and downside risk.
4. **Economic Forecasting:** Using silver as a proxy to understand broader market sentiment and industrial demand shifts.

---

##  Dataset Description

The dataset consists of cleaned and processed daily time-series data:

| Feature | Description |
| --- | --- |
| `Date` | Daily timestamp from Jan 2016 to March 2026. |
| `Predicted_Price` | The primary forecasted value for Silver ($/oz). |
| `Lower_Bound` | The pessimistic/conservative boundary of the price forecast. |
| `Upper_Bound` | The optimistic/aggressive boundary of the price forecast. |
| `Month` | Encoded month index for seasonality analysis. |

---

##  Methodology & Technical Stack

### Technologies Used:

* **Python:** For data ingestion and statistical computation.
* **Pandas:** Used for time-series manipulation and date-index alignment.
* **Forecasting Models:** Structured using time-series frameworks (likely Prophet or ARIMA based on the boundary logic) to handle trend and seasonality.
* **Matplotlib/Seaborn:** For visualizing the "Fan Chart" showing forecast confidence intervals.

### Analytical Workflow:

1. **Data Acquisition & Cleaning:** Aggregating historical silver price data and handling missing market days.
2. **Trend Decomposition:** Isolating the underlying growth trend from short-term market noise.
3. **Volatility Modeling:** Calculating the `Upper_Bound` and `Lower_Bound` to represent a 95% confidence interval for future pricing.
4. **Forecast Extension:** Projecting values into 2026 to provide a 2-year forward-looking perspective.

---

##  Key Insights (Executive Summary)

* **Long-Term Bullish Trend:** The analysis indicates a significant upward trajectory, with predicted prices rising from a mean of ~$17/oz in 2016 to over **$53/oz by Q1 2026**.
* **Volatility Analysis:** The model accounts for an average spread of approximately $13.5 between upper and lower bounds, suggesting high sensitivity to macroeconomic shifts.
* **Growth Milestone:** The forecast predicts that silver will sustain a level above $50/oz by early 2026, representing a potential ~200% growth over the 10-year study period.
* **Seasonality:** Monthly data indicates specific recurring patterns in price fluctuations, likely tied to industrial procurement cycles.

---

##  How to Use

1. **Clone the Repository:**
```bash
git clone https://github.com/vnandini879/silver-forecast-2026-EDA1-python.git

```


2. **Requirements:** Ensure you have Python installed with the necessary libraries:
```bash
pip install pandas matplotlib seaborn

```


3. **Visualization:** Use the provided scripts to plot the `Predicted_Price` against historical actuals to verify model accuracy.

---

##  Author

**Nandini Verma**

* **Role:** Business and Data Analyst
* **GitHub:** [vnandini879](https://www.google.com/search?q=https://github.com/vnandini879)

---

*Disclaimer: This analysis is for informational purposes only and does not constitute financial advice.*
