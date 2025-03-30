# 🏢 24S2-CB0494 Singapore HDB Resale Price Prediction 📈  

## 🔗 Project Links  
•	[GitHub Repo](https://github.com/gracenngg/24S2-CB0494-HDB-Price-Predictions.git)  
•	[View Rendered Notebook](https://nbviewer.org/github/gracenngg/24S2-CB0494-HDB-Price-Predictions/blob/941986f15fc04a7e9e67e69b109835a5ddaf9a96/CB0494_HDB_Price_Predictions.ipynb)  

## 🔭 Overview  

This project leverages machine learning algorithms to accurately predict Housing & Development Board (HDB) resale flat prices in Singapore. By applying advanced regression techniques to a comprehensive dataset of over 200,000 transactions, we've created a powerful price prediction model that achieves an **R² score exceeding 0.87** on test data.  

## 📊 Critical Performance Metrics  

| Model | Test RMSE (SGD) | Test R² | Test MAE (SGD) |  
|-------|-----------------|---------|----------------|  
| Linear Regression | 37,856.23 | 0.8523 | 28,342.15 |  
| Decision Tree | 34,761.41 | 0.8749 | 23,691.32 |  

## 🔍 Critical Findings  

1. **Most Important Factors Influencing Resale Prices:**  
   • **Floor area** is the strongest predictor, with larger units commanding significantly higher prices.  
   • **Location (town)** has a significant impact, with central regions showing premium pricing patterns.  
   • **Flat type** creates distinct pricing tiers, with 5-room and executive flats at a premium.  
   • **Floor level** demonstrates a consistent positive correlation with price.  
   • **Remaining lease** shows an evident influence on valuation decisions.  

2. **Model Performance:**  
   • Feature importance analysis reveals actionable insights for buyers and sellers.  
   • Our optimized Decision Tree model captures complex non-linear relationships in the housing market.  
   • The model handles categorical variables effectively through sophisticated preprocessing.  

3. **Practical Applications:**  
   • Insights provide strategic advantages for both buyers and sellers in negotiation contexts.  
   • Interactive pricing tool allows stakeholders to estimate property values with confidence.  
   • Methodology establishes a framework for ongoing market analysis as conditions evolve.  

## 💻 Technical Implementation  

This project demonstrates mastery of data science techniques, including:  

• **Advanced feature engineering** (lease calculation, categorical encoding, temporal feature extraction).  
• **Hyperparameter optimization** via grid search cross-validation.  
• **Interpretable visualizations** for complex multidimensional data.  
• **Robust model evaluation** with industry-standard metrics (MAE, RMSE, R²).  
• **Sophisticated data preprocessing** (pipelines, scalers, one-hot encoding).  

## 🛠️ Setup and Usage  

```bash  
# Clone this repository  
git clone https://github.com/gracenngg/24S2-CB0494-HDB-Price-Predictions.git  

# Navigate to the repository  
cd hdb-price-predictions  

# Install required packages  
pip install -r requirements.txt  

# Run the Jupyter notebook  
jupyter notebook HDB_Resale_Price_Predictions.ipynb  
=======  
# 24S2-CB0494: HDB Price Predictions  
 HDB Flat Price Predictions Using Machine Learning  
>>>>>>> 93188c1111653fcb7124f46ac0fbe19684a28a28  