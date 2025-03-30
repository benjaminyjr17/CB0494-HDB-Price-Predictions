# 🏢 24S2-CB0494 Singapore HDB Resale Price Prediction 📈

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/hdb-price-prediction)
![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/hdb-price-prediction)

## Overview

This project leverages machine learning algorithms to predict Housing & Development Board (HDB) resale flat prices in Singapore with exceptional accuracy. By applying advanced regression techniques to a comprehensive dataset of over 200,000 transactions, we've created a powerful price prediction model that achieves an R² score exceeding 0.87 on test data.

## 📊 Key Performance Metrics

| Model | Test RMSE (SGD) | Test R² | Test MAE (SGD) |
|-------|-----------------|---------|----------------|
| Linear Regression | 37,856.23 | 0.8523 | 28,342.15 |
| Decision Tree | 34,761.41 | 0.8749 | 23,691.32 |

## 🔍 Critical Findings

1. **Most Important Factors Influencing Resale Prices:**
   • **Floor area** is the strongest predictor, with larger units commanding significantly higher prices.
   • **Location (town)** has substantial impact, with central regions showing premium pricing patterns.
   • **Flat type** creates distinct pricing tiers, with 5-room and executive flats at the premium end.
   • **Floor level** demonstrates consistent positive correlation with price.
   • **Remaining lease** shows clear influence on valuation decisions.

2. **Model Performance:**
   • Our optimized Decision Tree model captures complex non-linear relationships in the housing market.
   • Feature importance analysis reveals actionable insights for buyers and sellers.
   • The model handles categorical variables effectively through sophisticated preprocessing.

3. **Practical Applications:**
   • Interactive pricing tool allows stakeholders to estimate property values with confidence.
   • Insights provide strategic advantages for both buyers and sellers in negotiation contexts.
   • Methodology establishes a framework for ongoing market analysis as conditions evolve.

## 💻 Technical Implementation

This project demonstrates mastery of data science techniques including:

- **Advanced feature engineering** (lease calculation, categorical encoding, temporal feature extraction).
- **Sophisticated data preprocessing** (pipelines, scalers, one-hot encoding).
- **Hyperparameter optimization** via grid search cross-validation.
- **Robust model evaluation** with industry-standard metrics (RMSE, R², MAE).
- **Interpretable visualizations** for complex multidimensional data.

## 🛠️ Setup and Usage

```bash
# Clone this repository
git clone https://github.com/yourusername/hdb-price-prediction.git

# Navigate to the repository
cd hdb-price-prediction

# Install required packages
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook HDB_Resale_Price_Prediction.ipynb