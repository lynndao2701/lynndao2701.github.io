---
title: "AI-Powered Analysis of Starbucks Customer Feedback using NLP & LDA"
excerpt: "Applied NLP and LDA topic modelling to unstructured Starbucks customer reviews to surface recurring themes around service quality, wait times, and staff management — enabling data-driven decision-making for customer experience improvement."
collection: portfolio
date: 2025-05-01
header:
  teaser: "https://static.wixstatic.com/media/nsplsh_3c93d671a0154cac9459e4febb19d56e~mv2.jpg/v1/crop/x_804,y_0,w_2391,h_3000/fill/w_322,h_404,al_c,q_80,enc_avif,quality_auto/Image%20by%20USAMA%20AKRAM.jpg"
---

## Overview

This project applies Natural Language Processing (NLP) and Latent Dirichlet Allocation (LDA) to analyse large volumes of unstructured Starbucks customer reviews, transforming raw feedback into actionable business insights. By automating topic discovery at scale, the solution identifies key customer concerns and tracks how they evolve over time — supporting data-driven decision-making for customer experience improvement.

Completed for **BUSA3001 – Artificial Intelligence in Business** at the University of Newcastle.

## What I Did

- Cleaned and prepared review text through normalisation, stopword removal, lemmatisation, and handling of missing values and date formatting
- Conducted exploratory text analysis including word frequency, sentiment categorisation, and review length analysis
- Built visualisations including word clouds, bigram and trigram charts, and temporal trend analysis to surface patterns quickly
- Applied **LDA topic modelling** using scikit-learn to identify dominant and emerging topics, then interpreted and labelled each topic in business terms
- Tracked how customer concerns evolved over time through topic trend analysis

## Key Insights

- Customer feedback was dominated by concerns around **service quality, wait times, and staff management**
- Negative reviews were more frequent and more detailed than positive ones
- Topic trends revealed persistent operational challenges and shifting customer priorities over time

## Tools & Techniques

Python, pandas, numpy, NLTK, scikit-learn, LDA, n-grams, tokenisation, lemmatisation, matplotlib, seaborn, wordcloud

## Outcome

The pipeline translated complex NLP outputs into decision-ready formats — word clouds, bigram charts, and topic trend graphs — demonstrating how unstructured customer feedback can be turned into clear, actionable insights for non-technical stakeholders and management teams.

[View on GitHub](https://github.com/lynndao2701/lda-topic-modeling-customer-reviews-starbucks)
