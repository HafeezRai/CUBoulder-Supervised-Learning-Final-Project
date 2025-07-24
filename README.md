# CUBoulder-Supervised-Learning-Final-Project

# Customer Churn Prediction Project

## Overview
This project predicts customer churn for a telecommunications company using supervised machine learning techniques. The goal is to identify customers at risk of leaving so that proactive retention measures can be implemented.

## Dataset
The project uses the Telco Customer Churn dataset from IBM, which contains information about:
- Customer demographics
- Services subscribed
- Account information
- Churn status

## Key Findings
- Achieved 80%+ accuracy in predicting customer churn
- Identified key factors influencing churn: contract type, monthly charges, and tenure
- Month-to-month contract customers have the highest churn risk

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## How to Run
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook

## Results
The optimized Random Forest model achieved:
- Accuracy: ~80%
- AUC Score: ~85%

## Business Recommendations
1. Focus retention efforts on month-to-month customers
2. Review pricing strategies for high-risk segments
3. Implement early intervention programs for at-risk customers
