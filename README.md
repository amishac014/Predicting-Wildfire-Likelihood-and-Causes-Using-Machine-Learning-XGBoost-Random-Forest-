# Predicting-Wildfire-Likelihood-and-Causes-Using-Machine-Learning-XGBoost-Random-Forest-
Comparative study using XGBoost and Random Forest to predict wildfire risk and classify fire causes from large-scale U.S. wildfire data.
Research & Development in Data Mining: Wildfire Prediction
Project Overview

This project presents a research-driven application of predictive data mining to forecast wildfire likelihood and identify probable causes using large-scale historical wildfire data from the United States. The study combines statistical analysis, machine learning, and model evaluation to support risk assessment and disaster management.

Dataset

The analysis uses the FPA Fire-Occurrence Database (1992–2015) containing over 1.8 million wildfire records with attributes such as:

Discovery date and time

Geographic location (state, county, latitude, longitude)

Fire size and duration

Fire cause categories

Land ownership information

Methodology
1. Wildfire Likelihood Prediction

Feature engineering: temporal features, previous-month fire count, location encoding

Models tested: Facebook Prophet, Random Forest, XGBoost

Final model: XGBoost Regressor with hyperparameter tuning

Evaluation: MAE, MSE, R²

Achieved moderate predictive performance with confidence interval estimation

2. Wildfire Cause Classification

Target: 13 NWCG fire cause categories

Handling class imbalance using SMOTE

Best model: Random Forest Classifier

Accuracy improved from ~62% to ~83% after resampling and tuning

Evaluation: Accuracy, Precision, Recall, F1-score

Key Contributions

Comparative analysis of time-series, ensemble, and classification models

Identification of important spatial and temporal predictors

Development of a CLI tool for real-time wildfire risk estimation with confidence bounds

Visualization of wildfire risk across U.S. states using maps and charts

Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, XGBoost, Prophet, Matplotlib, Seaborn, Folium, SMOTE, Jupyter Notebook

Outcome

This project demonstrates how advanced data mining and machine learning techniques can support early warning systems, resource planning, and policy decisions for wildfire management, and serves as a complete R&D-style portfolio project in predictive analytics.
