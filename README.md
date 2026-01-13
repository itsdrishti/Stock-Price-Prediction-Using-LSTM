# 📈 Stock Price Prediction using Machine Learning & Deep Learning

This project focuses on predicting stock prices using **Machine Learning and Deep Learning techniques**.  
The prediction is performed on **TCS (Tata Consultancy Services) stock data**, using both **Linear Regression** and **LSTM (Long Short-Term Memory)** models to analyze and forecast future stock prices.

---

## 🚀 Project Overview

Stock market prediction is a challenging task due to market volatility and non-linear patterns.  
In this project, historical stock price data of **TCS** is analyzed and used to build predictive models that can estimate future closing prices.

Two approaches are implemented:
- **Linear Regression** – for baseline prediction
- **LSTM Neural Network** – for capturing long-term dependencies in time-series data

---

## 🧠 Models Used

### 1️⃣ Linear Regression
- A simple machine learning model used for trend-based prediction
- Helps in understanding baseline performance
- Easy to interpret but less effective for complex time-series data

### 2️⃣ LSTM (Long Short-Term Memory)
- A type of Recurrent Neural Network (RNN)
- Designed specifically for time-series forecasting
- Captures temporal dependencies and patterns in stock prices
- Provides better performance in volatile market conditions

---

## 📂 Project Structure

```

├── Linear.ipynb        # Stock price prediction using Linear Regression
├── LSTM.ipynb          # Stock price prediction using LSTM model
├── TCS.NS.csv          # Historical stock data of TCS
└── README.md           # Project documentation

````

---

## 📊 Dataset Details

- **Source**: Yahoo Finance  
- **Stock**: TCS (Tata Consultancy Services)
- **File**: `TCS.NS.csv`
- **Features Used**:
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume

---

## ⚙️ Technologies & Libraries Used

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computation
- **Matplotlib** – Data visualization
- **Scikit-learn** – Linear Regression model
- **TensorFlow / Keras** – LSTM model
- **Jupyter Notebook**

---

## 🔍 Key Features

- Time-series stock price analysis
- Comparison between ML and DL approaches
- Data preprocessing and normalization
- Visualization of actual vs predicted prices
- Model performance comparison

---

## ▶️ How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
````

2. Navigate to the project folder:

```bash
cd your-repo-name
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Run:

* `Linear.ipynb` for Linear Regression
* `LSTM.ipynb` for LSTM-based prediction

---

## 📈 Results & Observations

* Linear Regression works well for simple trends but fails to capture market volatility.
* LSTM performs significantly better due to its ability to learn long-term dependencies.
* Deep Learning models are more suitable for stock market prediction tasks.

---

## 🔮 Future Improvements

* Add more technical indicators (RSI, MACD, Moving Averages)
* Use multiple stocks for comparison
* Improve accuracy using hyperparameter tuning
* Deploy the model using a web interface (Flask / FastAPI)
* Real-time stock prediction using live data

---

## 👨‍💻 Author

**Drishti Panthari**
Computer Science & Engineering Student| 
Machine Learning Enthusiast

---

## ⭐ Acknowledgements

* Yahoo Finance for stock data
* TensorFlow & Scikit-learn documentation
* Open-source ML community
