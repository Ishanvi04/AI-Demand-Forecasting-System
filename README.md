# 🧠 AI Demand Forecasting System

An end-to-end machine learning project that predicts future product demand using historical sales data, seasonality, and trend patterns. This system demonstrates the complete ML pipeline including data processing, feature engineering, model training, evaluation, and business interpretation.
**[Open Project in Google Colab](https://colab.research.google.com/drive/1yP6_BXTXWKJ2mNhpn9sdeuU5_OMSUnZw?usp=sharing)**


Project Highlights

- Dataset: 900,000+ real sales records
- Feature Engineering: Lag features, rolling averages, time-based features
- Models Used: Linear Regression, Random Forest
- Best Model: Random Forest (R² ≈ 0.92)
- Business Goal: Inventory optimization & revenue growth

RESULTS:

| Model | MAE | RMSE | R² |
|------|------|------|------|
| Linear Regression | 6.98 | 9.13 | 0.916 |
| **Random Forest** | **6.66** | **8.74** | **0.923** |

Business Insights

- The model captures strong seasonality and long-term growth patterns.
- Demand increases on weekends and mid-year months.
- Forecasting accuracy improvement of ~5–7% over baseline model.
- Enables better inventory planning and revenue optimization.

Tech Stack:
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab


