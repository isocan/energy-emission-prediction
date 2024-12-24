# Energy Consumption and CO2 Emission Prediction

## Project Overview
This project predicts energy consumption and CO2 emissions for various buildings based on their attributes. By employing machine learning models, the analysis identifies key factors affecting energy efficiency and offers actionable insights to reduce emissions.

## Objectives
- **Prediction**:
  - Forecast energy consumption and CO2 emissions for non-residential buildings.
  - Leverage building attributes like type, size, and energy sources.
- **Feature Analysis**:
  - Understand the impact of features like ENERGY STAR scores on predictions.
- **Interpretability**:
  - Provide clear explanations for model predictions using SHAP and LIME.

## Tools & Techniques
- **Data Preparation**:
  - Cleaned and transformed raw data, including handling outliers and missing values.
  - Applied feature engineering: ratio metrics, one-hot encoding, PCA for dimensionality reduction.
- **Modeling**:
  - Linear regression models: ElasticNet, Ridge, and Lasso.
  - Non-linear models: Support Vector Regression (SVR), Random Forest, XGBoost.
  - Optimized models using GridSearchCV.
- **Evaluation Metrics**:
  - R² Score
  - Mean Absolute Error (MAE)
- **Interpretability**:
  - LIME for local feature importance.
  - SHAP for global feature analysis.

## Key Results
- **Best Model**:
  - XGBoost achieved the highest performance (R²: 0.896 for emissions, 0.860 for energy).
- **Feature Insights**:
  - ENERGY STAR scores strongly correlate with energy efficiency.
  - Small-sized buildings with high ENERGY STAR scores exhibit lower emissions.
- **Interpretability**:
  - SHAP and LIME provided actionable insights into energy inefficiency causes.

## Deliverables
- **Jupyter Notebooks**:
  - Data exploration, preprocessing, and feature engineering.
  - Model training and evaluation.
- **Presentation**:
  - Summarized findings and recommendations for energy efficiency improvements.
- **Code**:
  - Scripts for feature engineering, training, and interpretability analysis.

## Future Work
- Expand the analysis with additional features like renewable energy integration.
- Incorporate time-series modeling for seasonal energy consumption patterns.
- Deploy the model for real-time building energy monitoring.
