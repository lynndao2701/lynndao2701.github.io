---
title: "Predicting Corporate Default Risk Using Machine Learning"
excerpt: "Applied machine learning to predict corporate default probability using financial ratios, ESG scores, and industry data — comparing Decision Tree, Logistic Regression, Random Forest, and SVM models to achieve up to 92% accuracy."
collection: portfolio
header:
  teaser: "https://static.wixstatic.com/media/nsplsh_05803868cce447869d3b0c610f47b4b6~mv2.jpg/v1/crop/x_1406,y_0,w_3188,h_4000/fill/w_322,h_404,al_c,q_80,enc_avif,quality_auto/Image%20by%20Austin%20Hervias.jpg"
---

## Overview

This project builds machine learning models to predict corporate default risk using firm-level financial ratios, cash flow indicators, ESG scores, and industry data. It demonstrates how financial and non-financial factors contribute to default probability, and how model tuning and comparison improve prediction accuracy and interpretability for credit risk assessment.

Completed for **FINN2003** at the University of Newcastle.

## What I Did

- Constructed a dataset of 100,000 simulated firm-level observations covering debt-to-asset ratio, current ratio, ROA, firm size, cash flow to debt, ESG score, and industry sector
- Built and interpreted a **Decision Tree classifier** as the primary model, tuned via entropy, max depth, and min leaf parameters to achieve 91% accuracy
- Benchmarked against **Logistic Regression (92%), Random Forest (91.5%), and SVC (92%)** with full performance metric comparison
- Conducted correlation analysis and feature importance analysis to identify the strongest predictors of default
- Applied data scaling and robustness checks to improve model generalisation

## Key Findings

- Higher leverage significantly increases default probability
- Stronger liquidity, profitability (ROA), and cash flow reduce risk
- Larger firms show lower default likelihood
- Poor ESG performance has a small but meaningful positive association with default risk
- Model tuning improved Decision Tree performance by approximately 3%

## Tools & Techniques

Python, Decision Tree, Logistic Regression, Random Forest, SVC, scikit-learn, data scaling, hyperparameter tuning, correlation analysis, ROC curve, classification metrics

## Outcome

The project demonstrated how machine learning can support credit risk assessment, helping investors and financial institutions better understand default probabilities using interpretable and comparative modelling across multiple algorithms.

[View on GitHub](https://github.com/lynndao2701/Predicting-Corporate-Default-Risk-Using-Machine-Learning--ML-)
