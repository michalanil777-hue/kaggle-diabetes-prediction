# Diabetes Probability Prediction (Kaggle Playground Series 2025)

## 📌 Project Overview
This project predicts the probability that a patient will be diagnosed with diabetes using a synthetic healthcare dataset from the Kaggle Playground Series 2025.

The solution focuses on:
- Proper cross-validation
- Handling categorical features
- ROC-AUC evaluation
- Production-ready ML workflow

## 🧠 Problem Statement
Given patient health indicators, predict the probability of diabetes diagnosis (`diagnosed_diabetes`).

## 📊 Dataset
- Source: Kaggle Playground Series 2025
- Data generated from a deep learning model trained on CDC Diabetes Health Indicators
- Mixed numerical and categorical features

⚠️ Dataset files are not included in this repository due to Kaggle rules.

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- CatBoost
- LightGBM (optional ensemble)

## 🔍 Model Approach
- Stratified K-Fold Cross-Validation (5 folds)
- CatBoostClassifier for native categorical handling
- ROC-AUC as evaluation metric
- Probability averaging across folds

## 📈 Results
- Cross-validation AUC: ~0.72
- Public Kaggle Leaderboard AUC: **0.699**
- Rank: ~700+

## 📂 Repository Structure
