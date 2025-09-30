# 📊 Demand Forecasting for a Retail Store  

## 📌 Project Overview  
This project applies **time series forecasting techniques** to predict future sales demand for a retail store using historical sales data.  
The dataset contains information about **Date, Sales, Price, and Stock**, which are analyzed to uncover **trends, seasonality, and patterns**.  

Forecasting demand helps retail businesses optimize **inventory management, pricing strategies, and supply chain decisions**.  

---

## 📊 Dataset  
**File:** mock_kaggle.csv  

**Features:**  
- `Date` → Transaction date  
- `Sales` → Units sold  
- `Price` → Selling price of items  
- `Stock` → Available stock in store  

---

## 🛠️ Technologies Used  
- Python 3  
- pandas  
- numpy  
- matplotlib & seaborn  
- statsmodels (SARIMA)  
- scikit-learn  

---

## 🚀 Steps in the Project  
1. **Data Loading & Cleaning**  
   - Converted date to `datetime` format  
   - Sorted dataset chronologically  
   - Checked for missing values  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized **sales trends** over time  
   - Identified **seasonality** (monthly/weekly patterns)  
   - Analyzed effect of **Price & Stock on Sales**  

3. **Modeling**  
   - Implemented **SARIMA (Seasonal ARIMA)** for forecasting  
   - Trained on historical data  
   - Forecasted **next 30 days of demand**  

4. **Model Evaluation**  
   - Metrics: **MAE, RMSE, MAPE**  
   - Compared actual vs predicted demand  

---

## 📈 Results  
- Clear **seasonality trends** observed in sales  
- **SARIMA model** performed well for short-term forecasts  
- Forecast for the **next 30 days** generated and saved as `forecast_next_30_days.csv`  

---
## ▶️ How to Run  

1. Clone the repository:  
```bash
git clone https://github.com/your-username/demand-forecasting-retail.git
cd demand-forecasting-retail
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the notebook or script:
```bash
jupyter notebook Demand_Forecasting.ipynb
```
or

```bash
python demand_forecasting.py
```

---

## 📌 Future Improvements
-Try advanced models (Prophet, LSTM, XGBoost).
-Include holiday effects & promotions for better accuracy.
-Deploy as a Streamlit/Flask web app for real-time demand prediction.

✍️ Developed by **Durga Damai** as part of **CodeClause Internship**.
