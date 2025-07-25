**📈 Stock Price Prediction (Next-Day Closing Price)**
This project predicts the next day's closing stock price using historical stock data fetched from Yahoo Finance via the yfinance Python library. It uses Linear Regression and Random Forest models to forecast stock prices based on features like Open, High, Low, Volume.

**🚀 Project Objective**
Predict short-term (next day) stock prices using basic regression techniques on time-series data.

**🛠️ Features**
Fetch historical stock data using yfinance API.

Build predictive models using Linear Regression and Random Forest.

Plot actual vs predicted closing prices.

Predict the next day's closing price.

Evaluate model performance using RMSE (Root Mean Squared Error).

**🧑‍💻 Technologies Used**
Python

pandas

numpy

yfinance

scikit-learn (Linear Regression, Random Forest)

matplotlib

**📊 Dataset**
Source: Yahoo Finance

Retrieved dynamically via yfinance Python package.

Features used:

Open

High

Low

Volume

(Target) Next Day's Close Price

**📝 Instructions to Run the Project**
Clone the Repository
git clone https://github.com/Nasir-Raza-AI/Stock-Price-Prediction.git
cd Stock-Price-Prediction

**Install Required Libraries**

pip install -r requirements.txt
Run the Python Script
python stock_price_prediction.py
(Optional) Use Jupyter Notebook for interactive exploration:

jupyter notebook
📈 Output Example
Actual vs Predicted Closing Prices plotted.

RMSE values for both Linear Regression and Random Forest models.

Prediction for the next day's closing price.

**🔍 Example Results**
mathematica
Copy
Edit
Linear Regression RMSE: 2.45
Random Forest RMSE: 1.83

Predicted Next Close Price (Linear Regression): $195.34
Predicted Next Close Price (Random Forest): $194.97

**🧩 Possible Improvements**
Add technical indicators (Moving Average, RSI).

Use LSTM or other Deep Learning models.

Incorporate sentiment analysis from news articles.

Deploy as a web dashboard for real-time predictions.

**📄 License**
This project is licensed under the MIT License.

**🙌 Acknowledgements**
Yahoo Finance

yfinance Python Library

scikit-learn

**📬 Contact**
For any questions or suggestions:

M. Nasir Raza

Email: nasir.raza7404@example.com

GitHub: Nasir-Raza-AI
