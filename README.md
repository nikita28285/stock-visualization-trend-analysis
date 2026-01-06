# Stock Visualization & Trend Analysis

This project analyzes nearly 20 years of historical stock data and visualizes price trends over time.  
It focuses on helping users understand market behaviour — not predicting future prices.

Data is loaded automatically using the `yfinance` library each time the notebook runs, so the analysis always stays updated.

---

##  Objectives

- Understand how stock prices move over long periods  
- Visualize patterns such as growth, dips, and volatility  
- Compare closing, opening, high, and low values  
- Support data-driven observation (without forecasting)

---

##  Features

- Load historical stock data directly from Yahoo Finance  
- Time-series trend visualization  
- Line charts for price movement  
- Comparison of multiple price metrics  
- Clean, reproducible Jupyter Notebook workflow  

---

##  Machine Learning (LSTM)

Along with visualization, I experimented with an **LSTM Neural Network** for learning purposes.

**Purpose**

- Understand how sequence models handle time-series data  
- Compare model behaviour vs real market trends  

> Note: This project focuses mainly on visualization and learning — not full production forecasting (yet).

---

##  Tech Stack

- Python  
- Jupyter Notebook  
- yfinance  
- pandas  
- matplotlib  
- TensorFlow / Keras (LSTM Neural Network)

---

##  Project Structure

You can explore the project directly on GitHub:

- **/notebooks** → main analysis notebook  
- **/code** → Python scripts (VS Code)  
- **/reports** → project report and explanations  
- **/data** → explains automatic data loading  
  

GitHub renders notebooks and documents automatically, so you can review everything without downloading.

---

##  Running the Interactive App (Streamlit)

This project also includes a Streamlit web app that runs through VS Code.

The app lets you:

- enter a stock/company ticker  
- view historical charts  
- see predicted values from LSTM  
- compare real vs predicted trends  

To run:
pip install streamlit yfinance pandas matplotlib tensorflow
streamlit run code/app.py

(Replace `app.py` if your filename is different.)

---

## 🚀 How to Run Locally (Notebook)

Open the notebook in /notebooks

Install dependencies:
pip install yfinance pandas matplotlib tensorflow

Run all cells

Data loads automatically and charts are generated


---

##  Project Report

A detailed project report is available in the **/reports** folder. It includes:

- project background & problem statement  
- data collection using yfinance  
- visualization results  
- LSTM explanation  
- screenshots of real outputs  
- comparison: actual vs predicted values  
- conclusions and observations  

---

##  About This Project

This project is part of my learning journey in data analytics and machine learning.  
It demonstrates data sourcing, visualization, trend interpretation, and early neural-network experimentation.

