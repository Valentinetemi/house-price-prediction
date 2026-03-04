<div align="center">

# 🏠 House Price Prediction

*A beginner-friendly machine learning project — from raw data to real predictions*

[![Python](https://img.shields.io/badge/Python-3.10-f4a7b9?style=flat-square&logo=python&logoColor=1a0a0f)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Linear%20Regression-e8d5f5?style=flat-square&logo=scikitlearn&logoColor=1a0a0f)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-f4a7b9?style=flat-square&logo=pandas&logoColor=1a0a0f)](https://pandas.pydata.org/)
[![R²](https://img.shields.io/badge/R²%20Score-0.65-e8d5f5?style=flat-square)](#)
[![Article](https://img.shields.io/badge/Read%20the%20Article-Medium-f4a7b9?style=flat-square&logo=medium&logoColor=1a0a0f)](https://temiloluwaval.medium.com/predict-house-prices-with-python-a-beginners-machine-learning-guide-9c73590508b2)

</div>

---

## Overview

This project walks through building a **Linear Regression model** to predict house prices using real housing data from Kaggle. It covers the full ML pipeline — data loading, feature engineering, model training, evaluation, and prediction.

Built as a companion to the Medium article: **[Predict House Prices with Python: A Beginner's ML Guide](https://temiloluwaval.medium.com/predict-house-prices-with-python-a-beginners-machine-learning-guide-9c73590508b2)**

---

## Model Results

| Metric | Score |
|--------|-------|
| R² Score | 0.65 |
| Mean Absolute Error | ~₦970,000 |
| Algorithm | Linear Regression |
| Train/Test Split | 80% / 20% |

---

## Features Used

| Feature | Type |
|---------|------|
| `area`, `bedrooms`, `bathrooms`, `stories`, `parking` | Numerical |
| `mainroad`, `guestroom`, `basement`, `hotwaterheating` | Binary (yes/no → 1/0) |
| `airconditioning`, `prefarea` | Binary (yes/no → 1/0) |
| `furnishingstatus` | Categorical (one-hot encoded) |
| `price` | Target variable |

---

## Quickstart

**1. Clone the repo**
```bash
git clone https://github.com/Valentinetemi/house-price-prediction.git
cd house-price-prediction
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Get the dataset**

Download the [Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset) from Kaggle and place `Housing.csv` in the project folder.

**4. Run the notebook**

Open `house_price_prediction/` in Google Colab or Jupyter and run all cells.

---

## ML Pipeline

```
Load Data → Prepare Features → Encode Categorical Columns
    → Train/Test Split → Train Model → Evaluate → Predict
```

---

## What You'll Learn

- How to load and explore real-world data with Pandas
- How to encode categorical and binary features for ML
- Why train/test splits matter and how to use them
- How to train a Linear Regression model with Scikit-Learn
- How to evaluate with R² score and MAE
- How to make predictions on unseen data

---

## About the Author

Built by **[Temiloluwa Valentine](https://github.com/Valentinetemi)** — Computer Vision Engineer & AI/ML Developer based in Nigeria.

📖 Read more on **[Medium](https://medium.com/@temiloluwaval)** · **[Dev.to](https://dev.to/temiloluwavalentine)**

---

<div align="center">
<sub>Found this helpful? Drop a ⭐ — it means a lot!</sub>
</div>
