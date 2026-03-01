# 📈 Yahoo Stock Price Forecasting using Meta Prophet



## 📌 Project Overview
Predicting the stock market is a notoriously difficult task due to its volatility and non-stationary nature. In this project, I applied machine learning to historical Yahoo stock data (2015–2020) to forecast future 'Close' prices. 

Using **Meta's Prophet** library, I built a robust time-series forecasting model that accounts for weekly/yearly seasonality and the impact of US holidays on market behavior.

## 🚀 Key Features & Methodology
* **Exploratory Data Analysis (EDA):** Analyzed 5 years of stock data and handled outliers.
* **Stationarity Testing:** Utilized the Augmented Dickey-Fuller (ADF) test to confirm the non-stationary nature of the financial data.
* **Holiday Effects:** Incorporated a custom US holidays calendar to improve prediction accuracy during market anomalies.
* **Cross-Validation:** Evaluated model performance over a 365-day horizon using metrics like Mean Absolute Percentage Error (MAPE).
* **Hyperparameter Tuning:** Implemented a Grid Search to optimize the `changepoint_prior_scale` and `seasonality_prior_scale`.



## 🛠️ Tools & Libraries Used
* **Python** (Pandas, NumPy)
* **Meta Prophet** (Time-series modeling)
* **Matplotlib / Seaborn** (Data visualization)
* **Scikit-learn** (Model evaluation)

## 📊 Results
The final optimized model successfully generated a 365-day forecast, identifying clear seasonal trends and providing a baseline for future stock price movements. 

## 📂 Files in this Repository
* `aayahoo_stock.ipynb`: The main Jupyter Notebook containing all EDA, modeling, and tuning.
* `yahoo_stock.csv`: The historical dataset used for training.

## 💡 How to Run
1. Clone this repository.
2. Install the required dependencies: `pip install pandas numpy prophet matplotlib`
3. Run the Jupyter Notebook to view the interactive plots and forecasts.
