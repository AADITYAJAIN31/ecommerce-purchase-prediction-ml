# E-commerce Purchase Intent Prediction

## Problem Statement
Predict whether a visitor will complete a purchase based on session-level
browsing behavior in an e-commerce website.

## Dataset
- 12,330 individual user sessions
- Mix of numerical and categorical features
- Each session represents a unique visitor
- Highly imbalanced target variable (Purchase vs No Purchase)

## Approach
- Performed Exploratory Data Analysis (EDA) to understand user behavior
- Applied preprocessing for mixed feature types
- Built a Decision Tree classifier as an interpretable baseline model
- Evaluated performance using F1-score due to class imbalance

## Results
- Accuracy: ~87%
- F1-score: ~0.52
- Identified key behavioral features influencing purchase intent

## Model Explainability
- Visualized decision tree structure
- Analyzed feature importance to understand decision rules

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
