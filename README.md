# 🏠 Housing Price Prediction (LightGBM / XGBoost / Random Forest)

This project is a machine learning pipeline for predicting housing prices based on features such as carpet area, BHK, location, amenities, floor details, and more.  
It includes:

- Data cleaning & feature engineering  
- Price parsing from text (e.g., "1.2 Cr", "80 Lac")  
- LightGBM, XGBoost, and Random Forest model comparison  
- A custom prediction function for new unseen property data  
- Visualizations and feature importance  

The project is implemented in **Python** using a **Jupyter Notebook (`.ipynb`)**.

---

## Features

- Cleans and preprocesses raw real-estate data  
- Handles categorical features and rare category grouping  
- Supports numeric extraction from messy fields  
- Trains and compares 3 ML models  
- Deployable prediction function using LightGBM  
- Easy to modify for new datasets  

---

## Requirements

Install dependencies:

```bash
pip install pandas numpy scikit-learn lightgbm xgboost matplotlib seaborn joblib

##Running the Project
Run in Google Colab (Recommended)

Upload the .ipynb file to Colab
Upload your dataset (house_prices.csv)
Run all cells without installing Jupyter locally

## Dataset Source

This project uses a publicly available real-estate dataset from Kaggle:

**Kaggle Dataset:**  
Link: https://www.kaggle.com/datasets/juhibhojani/house-price?resource=download
