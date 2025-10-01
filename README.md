# AQI Prediction: ML/DL Comparative Study

Comparative analysis of machine learning and deep learning models for Air Quality Index prediction using global pollution data.

## 🎯 Key Results

### Model Performance Comparison

| Model | RMSE | R² Score |
|-------|------|----------|
| Deep MLP (256-128-64-32) | 7.72 | 0.910 |
| Random Forest | 7.79 | 0.910 |
| K-Nearest Neighbors | 7.85 | 0.909 |
| Support Vector Regression | 8.59 | 0.891 |
| Gradient Boosting | 8.75 | 0.887 |
| MLP (128-64-32) | 8.22 | 0.900 |
| CNN-MLP Hybrid | 8.77 | 0.886 |
| Linear Regression | 11.25 | 0.813 |

### Key Findings
- **Best Models:** Random Forest and Deep MLP achieved 91% R² accuracy
- **Feature Importance:** PM2.5 and PM10 identified as dominant AQI predictors
- **Practical Accuracy:** RMSE of 7.72-7.79 represents ~1.5% error on 0-500 AQI scale
- **Dataset Scale:** 52,000+ daily records from 6 cities (Jan-Dec 2024)

## 📊 Dataset

**Source:** [Air Quality 2024 - Kaggle](https://www.kaggle.com/datasets/youssefelebiary/air-quality-2024)

The dataset contains daily measurements of CO, NO₂, SO₂, O₃, PM2.5, and PM10 from 6 globally distributed cities throughout 2024.

- **Size:** 52,000+ daily records
- **Period:** January - December 2024
- **Cities:** 6 globally distributed cities
- **Pollutants:** CO, NO₂, SO₂, O₃, PM2.5, PM10
- **Format:** CSV

## 🔧 Tech Stack

Python | Scikit-learn | PyTorch | Pandas | NumPy

## 📄 Full Report

[Read the complete research paper](report.pdf)

## 👤 Authors
Md. Rakibur Rahman Shovon | [shovonrakiburrahman3@gmail.com]
Nishat Tasnim Luba | [nishat.tasnim.luba@g.bracu.ac.bd]
Md. Mostofa All Zubayer | [mostofa.all.zubayer@g.bracu.ac.bd]
