# Recession Prediction System 📉📊

### Overview
This project is a Flask-based web application designed to predict the probability of U.S. recessions using over 100 years of economic data from the **Federal Reserve Economic Data**. The goal is to identify early warning signs of economic downturns to assist policymakers, investors, and corporations in making informed decisions. By leveraging advanced **statistical** and **machine learning models**, this system enhances early warning capabilities.

### Features
- **Rare-Event Prediction**: Forecasts economic recessions, which are relatively rare but significant events.
- **Key Economic Indicators**: The model uses important indicators such as Treasury Bond Interest Rates, GDP, CPI, Unemployment Rate, Stock Price Index (S&P), and Federal Funds Rate.
- **Time Series Analysis**: Analyzes historical trends in economic data to predict future recessions.

### Tools & Technologies Used 🔧:
- **Languages**: Python 🐍 <br>
- **Frameworks**: Flask 🌐 <br>
- **Libraries**:
    - Machine Learning: scikit-learn, XGBoost, Probit, Elastic Net, SVM, KNN, Naïve Bayes <br>
    - Data Handling: pandas, numpy <br>
    - Visualization: matplotlib, seaborn <br>
- **Database**: Federal Reserve Economic Data (FRED) 📉

### Models & Techniques
- **Machine Learning Models**:
  - **Logistic Regression**: Standard model for binary classification.
  - **Probit Model**: Used to estimate the probability of recessions.
  - **Elastic Net**: Regularization technique to improve model performance.
  - **XGBoost**: Gradient boosting for improved accuracy.
  - **SVM, KNN, Naïve Bayes**: Additional models explored for comparison.
- **Error Metric**:
  - **Log-Loss**: Used as the evaluation metric for binary classification, measuring how close the prediction probabilities are to the actual outcomes.
 
### Key Insights
 - **Unemployment Rate**: Lags recessions but serves as an important post-recession indicator.
 - **Treasury Bond Rates**: Effective for predicting economic downturns, particularly the 10-Year vs. 3-Month spread.
 - **CPI & Inflation**: Rising inflation often precedes economic slowdowns.


