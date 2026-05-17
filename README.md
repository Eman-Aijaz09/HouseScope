# HouseScope
Automated ML Pipeline for House Price Prediction


HouseScope AI is an intelligent real estate valuation system that predicts current housing prices and generates future price forecasts using advanced ensemble machine learning techniques.

The project combines XGBoost, LightGBM, and CatBoost models with Bayesian hyperparameter optimization and SHAP explainability to deliver accurate, interpretable, and scalable house price predictions.

---

## Project Overview

This project was developed to address two main objectives:

- Accurate prediction of current residential property prices
- Five-year future forecasting under multiple economic scenarios

The system performs:
- Automated preprocessing
- Feature engineering
- Model training and tuning
- Ensemble blending
- Explainable AI analysis
- Inflation-adjusted future forecasting
- Interactive visualization through Gradio

---

## Key Features

- Ensemble learning using:
  - XGBoost
  - LightGBM
  - CatBoost

- Bayesian hyperparameter optimization using Optuna

- SHAP-based model interpretability

- Feature engineering pipeline

- Inflation-adjusted market forecasting

- Interactive Gradio interface

- Residual analysis and overfitting checks

- Portfolio-level property analysis

---

## Dataset

The project uses the Ames Housing Dataset containing residential housing data with multiple structural, quality, and neighborhood-related features.

Training data spans:
- 2006–2010 housing market records

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Optuna
- SHAP
- Gradio
- Matplotlib
- Seaborn
- Plotly

---

## Model Architecture

The final prediction system uses a weighted ensemble of:

| XGBoost | Robust gradient boosting |
| LightGBM | Fast histogram-based boosting |
| CatBoost | Native categorical handling |

Optuna was used to optimize:
- Individual model hyperparameters
- Ensemble blend weights

---

Top predictive features included:

- OverallQual
- GrLivArea
- ExterQual
- GarageCars
- KitchenQual
- TotalBsmtSF
- YearBuilt

SHAP analysis was used to explain:
- Global feature importance
- Individual property predictions

---

## Forecasting System

The project includes a five-year forecasting module (2026–2030) using:
- Housing Price Index (HPI)
- Inflation-adjusted projections
- Scenario-based growth modeling

### Forecast Scenarios
- Conservative
- Base Case
- Optimistic

---

## Explainable AI

HouseScope AI integrates SHAP explainability to provide transparent predictions.

The interface displays:
- Positive feature contributions
- Negative feature contributions
- Dollar-level impact of each feature

This improves trust and interpretability for stakeholders.

---

## Project Structure

```text
HouseScope-AI/
│
├── notebooks/
│   └── housescope.ipynb
│
├── report/
│   └── HouseScope_AI.pdf
│
├── images/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

Clone the repository:


Install dependencies:

pip install -r requirements.txt

---

## Running the Project

Open the notebook:

jupyter notebook

Or run directly in Google Colab.


## License

This project is for educational and research purposes.
