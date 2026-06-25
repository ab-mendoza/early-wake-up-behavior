# early-wake-up-behavior
A data-driven exploration of the factors associated with early waking through statistical analysis and predictive modeling.

# Early Wake-Up Behavior: Lifestyle Patterns and Predictive Factors Using Machine Learning

## Overview

This project explores the factors associated with early wake-up behavior through exploratory data analysis and machine learning techniques.

The objective is not to determine whether waking up early directly causes better outcomes, but rather to investigate which lifestyle, behavioral, health, and psychological factors are associated with early waking patterns and how accurately these patterns can be predicted.

The analysis combines statistical exploration, correlation analysis, and supervised machine learning to identify meaningful relationships while considering limitations such as confounding variables and the inability to establish causality from observational data.

---

## Research Questions

- Are early wakers associated with different lifestyle and behavioral patterns?
- Which factors show the strongest relationship with early wake-up behavior?
- Can machine learning models accurately predict early waking patterns?
- Which variables contribute most to the model's predictions?

---

## Dataset

The dataset contains information related to:

- Demographics
- Sleep habits and quality
- Physical activity and fitness
- Nutrition and hydration
- Lifestyle habits
- Mental well-being
- Productivity and cognitive indicators
- Health-related measurements

The target variable is:

**Early_Waker**  
- 1 → Early waker  
- 0 → Non-early waker

---

## Methodology

The project follows these steps:

1. Data quality assessment
   - Missing values analysis
   - Duplicate detection

2. Exploratory Data Analysis
   - Demographic patterns
   - Sleep behavior analysis
   - Health indicators
   - Exercise and nutrition patterns
   - Mental well-being and productivity analysis
   - Correlation analysis

3. Machine Learning Modeling
   - Feature preprocessing
   - Model comparison
   - Hyperparameter optimization
   - Final model selection

4. Model Evaluation
   - Classification metrics
   - ROC-AUC analysis
   - Precision-Recall analysis
   - Feature influence interpretation

---

## Machine Learning Models

The following classification algorithms were evaluated:

- Logistic Regression
- XGBoost

The final model selected was:

**Logistic Regression**

Reason:
- Best performance on unseen test data
- Lower risk of overfitting
- Greater interpretability

---

## Key Findings

- Early waking showed stronger associations with routines, productivity, and psychological indicators than with direct health measurements.
- Sleep quality appeared to have a stronger relationship with several well-being indicators than wake-up time alone.
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
