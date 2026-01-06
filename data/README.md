# Stock Visualization & Trend Analysis

This project analyzes nearly 20 years of historical stock data and visualizes price trends over time.  
It focuses on helping users understand market behaviour — not predicting future prices.

Data is loaded automatically using the `yfinance` library each time the notebook runs, so the analysis always stays updated.

If you want to run the project:
- Open the notebook in /notebooks
- Run the cells
- The data will download automatically

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
1. Open the notebook in /notebooks
2. Install dependencies:
   pip install yfinance pandas matplotlib tensorflow
3. Run all cells
4. Data loads automatically and charts are generated

## Running the Interactive App (Streamlit)

This project also includes a Streamlit web app that runs from VS Code.

The app allows users to:

enter a stock/company name (ticker symbol)

view historical price charts

see model-generated predicted values (LSTM)

compare real vs predicted trends side-by-side

## Project Report 

A detailed project report is available in the /reports folder.
It explains:

project background & problem statement

data collection using yfinance

visualization results with graphs

LSTM model explanation

screenshots of real outputs

comparison of actual vs predicted values

conclusion and observations
