# 🔍 FBI Crime Forecasting using Time Series 📈

[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange)](https://jupyter.org/)
[![View on NBViewer](https://img.shields.io/badge/View%20Notebook-NBViewer-brightgreen)](https://nbviewer.org/github/yourusername/reponame/blob/main/Copy_of_Sample_ML_Submission_Template.ipynb)

---

## 📌 Overview

This project aims to forecast monthly crime incident counts using historical FBI data. By analyzing temporal and categorical crime data, we use machine learning techniques to predict future crime levels across various types of offenses.

---

## 📁 Dataset Description

The dataset contains the following key features:
- **YEAR**: The year of the crime record
- **MONTH**: The month of the record
- **TYPE**: Type of crime committed (e.g., theft, assault, etc.)
- **Incident_Counts**: Number of crimes committed (engineered from grouping)

The original training file is in Excel format (`Train.xlsx`) and contains raw records that are grouped and encoded before modeling.

---
## ⚙️ Installation & Setup

Run the following commands to set up the environment:

```bash
# For macOS users (required for Prophet)
brew install libomp
# if using windows ignore libomp
# Python dependencies
pip install prophet
pip install pmdarima
pip install optuna
pip install pandas
pip install torch
pip install matplotlib
pip install scikit-learn
```
---
## 🎯 Objective

To build a model that can:
- Analyze historical crime data
- Understand temporal trends in criminal activity
- Forecast future crime counts for each crime type and month

---

## 💡 Approach

- Aggregated the data monthly per crime type
- Encoded categorical features for modeling
- Applied machine learning algorithms to train on historical trends
- Evaluated the model's prediction performance using appropriate metrics

---

## 📊 Tools & Technologies

- **Jupyter Notebook**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**
- **Label Encoding**
- **Random Forest Regressor**

---

## 📈 Results Summary

The trained model provides reasonable forecasts of crime activity based on:
- Past behavior of different crime types
- Monthly seasonality and patterns

The evaluation focuses on metrics such as MAE and RMSE to assess prediction accuracy.

---

## 🚀 Future Work

- Implement deep learning methods like LSTM or Transformer models for sequence prediction
- Incorporate external factors such as socio-economic data, holidays, or weather
- Improve data granularity by including location-based insights (e.g., city, district)

---

## 🙋‍♂️ Author

**Pavan Kumar Dirisala**  
🎓 B.Tech CSE (AI & IP), KL University  
🎸 Guitar Enthusiast | 🎧 Music Lover

---

