**Gold Price Prediction**

## Overview
This project predicts gold prices using machine learning models. Historical Gold Futures data is downloaded using the Yahoo Finance API and used to train Linear Regression and XGBoost models.

## Steps Followed
1. Data Collection using yfinance  
2. Data Cleaning (handling missing values)  
3. Feature Engineering (Moving Averages - MA10, MA50)  
4. Train-Test Split (80/20)  
5. Model Training:
   - Linear Regression
   - XGBoost Regressor
6. Evaluation using:
   - RMSE
   - R² Score
7. Visualization of predicted vs actual prices

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Files in this Repository
- `gold_price_prediction.ipynb` – Main Jupyter Notebook
- `README.md` – Project documentation

### How to Run
1. Open `gold_price_prediction.ipynb` in Google Colab or Jupyter.  
2. Verify required libraries in `requirements.txt`.  
3. Run all cells sequentially to reproduce results.


## Results
The XGBoost model performed the best with lower RMSE and higher R² score. The predicted trend closely matches the actual gold price movement.
