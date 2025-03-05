# 📈 Portfolio Management Optimization

This project focuses on **portfolio optimization** using **machine learning and deep learning** techniques to assist investors in selecting and allocating assets for maximum returns while minimizing risks. The solution integrates **classification models**, **time-series forecasting**, and **portfolio optimization strategies**.

## 🚀 Project Overview
The project follows a structured **CRISP-DM** methodology and includes the following key phases:

1. **Data Collection & Preprocessing**  
   - Extraction of historical stock prices using `yfinance`  
   - Feature engineering with financial indicators (Beta, Sharpe Ratio, Williams %R, ROC, etc.)  
   - Handling missing data and preparing structured datasets  

2. **Asset Selection (Machine Learning)**  
   - Clustering stocks based on financial indicators  
   - Classification of stocks into **growth-oriented** and **defensive** categories  
   - Models used: **KNN, Random Forest, SVM, Decision Tree, Logistic Regression**  

3. **Stock Price Prediction (Deep Learning)**  
   - **LSTM model** trained for time-series forecasting of stock prices  
   - Used to estimate future trends and refine asset selection  

4. **Portfolio Optimization**  
   - Asset allocation strategy using **Mean-Variance Optimization (MVO)** and **Efficient Frontier**  
   - Monte Carlo simulations to optimize the portfolio's **Sharpe Ratio**  
   - Comparison of **optimized portfolio vs. S&P 500 benchmark**  

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `TensorFlow/Keras`, `yfinance`, `PyPortfolioOpt`, `matplotlib`, `seaborn`  
- **Development Environment:** Jupyter Notebook  
