# ML_SP500

## Project Overview
This project explores the application of **Machine Learning models** to predict the closing prices of the S&P 500 index.  
The analysis focuses on **lagged variables as features**, evaluating how traditional regression and tree-based models behave when applied to financial time series.

The goal is not to achieve perfect forecasting, but to demonstrate **end-to-end workflow**:  
- Data retrieval with `yfinance`  
- Feature engineering (lags, autocorrelation check)  
- Model training & evaluation  
- Backtesting of trading strategies  
- Critical interpretation of results  

---

## Repository Structure
- **ML_SP500.ipynb** – Jupyter Notebook with full code, analysis, plots, and evaluation  
- **ML_SP500.html** – Exported HTML version of the notebook (easy to view without Jupyter)  
- **requirements.txt** – Required Python libraries  
