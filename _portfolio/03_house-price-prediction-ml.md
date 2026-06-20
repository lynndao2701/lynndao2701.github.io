---
title: "Multi-Agent ML System for House Price Prediction & Forecasting"
excerpt: "Built a hybrid machine learning framework combining Random Forest, ARIMA, and LSTM across a multi-agent architecture to predict individual property prices and forecast state-level housing market trends in Australia."
collection: portfolio

header:
  teaser: "https://static.wixstatic.com/media/nsplsh_d5fd79981bf940b092fd052a5eda2c60~mv2.jpg/v1/crop/x_703,y_0,w_1595,h_2001/fill/w_322,h_404,al_c,q_80,enc_avif,quality_auto/Image%20by%20Jakub%20%C5%BBerdzicki.jpg"
---

## Overview

This project develops a multi-agent machine learning system for house price prediction and market trend forecasting across Australia. The system operates at two scales — a micro-level agent for individual property valuation, and a macro-level agent for state-wide market forecasting — using a hybrid approach that combines supervised learning, time-series analysis, and metaheuristic optimisation.

Completed for **COMP3330** at the University of Newcastle.

## What I Did

- **Micro-level agent:** Trained Random Forest, Linear Regression, and Support Vector Regression (SVR) on 11,160 property listings from Kaggle (17 features), with preprocessing including missing value handling, categorical encoding, and outlier removal
- **Macro-level agent:** Built ARIMA and LSTM models on ABS state-level housing price data to forecast market trends at quarterly and long-term scales
- Applied **genetic algorithm metaheuristic optimisation** for hyperparameter tuning across ARIMA parameters, LSTM batch size, epoch count, and window size
- Evaluated models using R², RMSE, and MSE metrics across all approaches

## Results

| Model | Performance |
|---|---|
| Random Forest (micro) | R² ≈ 0.757, RMSE ≈ 336,505 |
| Linear Regression | R² ≈ 0.506, RMSE ≈ 479,850 |
| SVR | R² ≈ 0.367, RMSE ≈ 543,419 |
| ARIMA (macro) | Accurate short-term forecasts (1–2 quarters) |
| LSTM (macro) | Captures longer-term trends and seasonal patterns |

## Tools & Techniques

Python, Random Forest, Linear Regression, SVR, ARIMA, LSTM, genetic algorithm optimisation, pandas, scikit-learn, time-series forecasting, feature engineering, model evaluation

## Outcome

The system demonstrated how combining property-level and market-level intelligence in a multi-agent framework provides more complete and actionable insights for buyers, sellers, and investors — while showcasing applied skills in supervised learning, time-series modelling, and system architecture.

[View on GitHub](https://github.com/lynndao2701/MultiAgent-ML-System-for-House-Price-Prediction-and-Forecasting)
