# Early Wake-Up Behavior: Lifestyle Patterns and Predictive Factors Using Machine Learning

## Overview

This project explores the factors associated with early wake-up behavior through exploratory data analysis and machine learning.

The objective is not to determine whether waking up early causes better outcomes, but to investigate which lifestyle, behavioral, health, and psychological factors are associated with early waking patterns and how accurately these patterns can be predicted.

The analysis combines data exploration, correlation analysis, and supervised machine learning while considering limitations such as confounding variables and the inability to establish causality from observational data.

---

## Research Questions

- Are early wakers associated with different lifestyle and behavioral patterns?
- Which factors show the strongest relationship with early wake-up behavior?
- Can machine learning models predict early waking behavior?
- Which variables contribute most to these predictions?

---

## Dataset

The dataset contains information related to:

- Demographics
- Sleep habits and quality
- Physical activity and fitness
- Nutrition and lifestyle habits
- Mental well-being
- Productivity and cognitive indicators
- Health-related measurements

**Target Variable:**

`Early_Waker`

- 1 → Early waker
- 0 → Non-early waker

---

## Methodology

The project follows an end-to-end data science workflow:

1. **Data Quality Assessment**
   - Missing values analysis
   - Duplicate detection

2. **Exploratory Data Analysis**
   - Demographic, sleep, health, lifestyle, and behavioral patterns
   - Correlation analysis
   - Interpretation of key findings

3. **Machine Learning Modeling**
   - Feature preprocessing
   - Model comparison
   - Hyperparameter optimization
   - Final model selection

4. **Model Evaluation**
   - Classification metrics
   - ROC-AUC analysis
   - Precision-Recall analysis
   - Feature influence interpretation

---

## Machine Learning Models

The following classification models were evaluated:

- Logistic Regression
- XGBoost

The final model selected was:

**Logistic Regression**

Selection criteria:
- Best performance on unseen test data
- Lower risk of overfitting
- Greater interpretability

---

## Key Findings

- Early waking showed stronger associations with routines, productivity, and psychological indicators than with direct health measurements.
- Sleep quality appeared to have a stronger relationship with well-being indicators than wake-up time alone.
- Machine learning achieved moderate predictive performance, suggesting that early waking behavior can be partially explained by lifestyle patterns.
- Results should be interpreted as associations rather than causal effects.

---

## Tools and Libraries

Python libraries used:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

---

## Project Structure

```
Early-Wake-Up-Behavior/
│
├── Early_Wake_Up_Behavior.ipynb
├── README.md
└── dataset/
```

---

## Author

**Abraham [Last Name]**

Data Science Portfolio Project
