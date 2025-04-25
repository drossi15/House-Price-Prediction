# 🏠 NYC House Price Prediction

A machine learning project to predict house prices in New York using structured data and various regression models.

---

## 📂 Overview

- **Dataset**: Housing data from NYC (`NY-House-Dataset 2.csv`)
- **Link** : https://www.kaggle.com/datasets/nelgiriyewithana/new-york-housing-market
- **Goal**: Predict `PRICE` using numerical features + distance from city center (Times Square)
- **Models**:
  - Linear Regression
  - Random Forest Regressor
  - Multi-layer Perceptron (Neural Network)

---

## 🔧 Features & Processing

- Outlier removal via IQR (for price, sqft, beds, baths)
- Feature engineering: `DISTANCE_FROM_CENTER` (to Times Square)
- Train/Validation/Test split: 70/20/10
- Evaluation: MAE, MSE, R², Pearson correlation
