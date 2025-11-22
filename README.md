📊 Retail Store Sales Forecasting (Month-wise Prediction)

A Machine Learning–based application that predicts next year’s month-wise sales using previous year retail data. This project helps retail stores analyze sales trends, plan inventory, reduce stock losses, and make informed business decisions. The entire dashboard is built using Streamlit, with interactive charts and a manual month-selection feature.

🚀 Features

✔ Predict 12-month sales for the next year

✔ Allows manual selection of any month to view its prediction

✔ Interactive line and bar charts

✔ Uses Linear Regression for forecasting

✔ Simple and clean Streamlit UI

✔ No CSV upload needed — dataset already included

✔ Lightweight and fast

🧠 Technologies Used

Python 3.8+

Streamlit — Dashboard interface

Pandas — Data processing

NumPy — Numerical operations

Scikit-Learn (Linear Regression) — Predictions

Plotly — Interactive charts

VS Code / Jupyter Notebook — Development environment

📂 Project Structure
Retail-Sales-Forecasting/
│── app.py
│── dataset.csv    (optional if user adds)
│── README.md
│── requirements.txt

📈 How It Works

Previous year data (example: 2024) is stored inside the code.

Dates are converted into MonthIndex values (1–12).

A Linear Regression model is trained using:

MonthIndex → Sales


The model predicts the next 12 MonthIndex values (for 2025).

A Streamlit dashboard displays:

Predicted values

Month-wise table

Trend line chart

Bar chart

Selected-month predicted value

🧮 Machine Learning Model
Linear Regression

This model analyzes the relationship between month progression and sales.
It is ideal for short datasets (12 months) and gives smooth trend predictions.

Future enhancement options:

Prophet

ARIMA/SARIMA

Random Forest Regression

LSTM (Deep Learning)

▶️ How to Run the Project
1. Install dependencies
pip install -r requirements.txt

2. Run the Streamlit app
streamlit run app.py

3. Open the browser

Streamlit will open automatically at:

http://localhost:8501

📊 Sample Output (What You Will See)

📄 Previous Year Data Table

📈 Line Chart of Predicted Trend

📊 Bar Chart of Month-wise Predictions

🔍 Dropdown to select any future month

📌 Predicted Sales for selected month (Jan-Dec 2025)

🔮 Future Enhancements

Multi-year forecasting

Product-wise prediction

Download predicted results as CSV

Database-connected sales forecasting

Seasonal trend adjustment

ARIMA/Prophet forecasting integration

🤝 Contributing

Pull requests and suggestions are welcome!
Fork the repo → Create a branch → Submit PR.# sales_forecasting
