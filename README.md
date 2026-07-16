# Ultimate Technologies Take-Home Challenge

## Overview

This repository contains my solution to the **Ultimate Technologies Data Science Take-Home Challenge**, which evaluates skills in exploratory data analysis, experimental design, and predictive modeling.

The challenge is divided into three independent sections:

- **Part 1:** Analyze user login activity to identify temporal usage patterns.
- **Part 2:** Design an experiment to evaluate the effectiveness of a proposed rider incentive program.
- **Part 3:** Develop a machine learning model to predict long-term rider retention and identify the factors most strongly associated with customer churn.

The project demonstrates a complete data science workflow, from data exploration and visualization through model development, evaluation, interpretation, and business recommendations.

---

## Objectives

- Explore user behavior through visualization and descriptive statistics.
- Design a statistically sound experiment for product evaluation.
- Build predictive models for rider retention.
- Compare model performance using multiple evaluation metrics.
- Translate analytical findings into actionable business recommendations.

---

## Methods

### Data Analysis

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Correlation analysis
- Data visualization

### Machine Learning

Two classification models were developed and compared:

- Logistic Regression
- Random Forest

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC
- Confusion Matrix
- ROC Curve

---

## Results

The **Random Forest** classifier outperformed Logistic Regression across nearly every evaluation metric.

| Metric | Logistic Regression | Random Forest |
|--------|--------------------:|--------------:|
| Accuracy | 0.719 | **0.755** |
| Precision | 0.675 | **0.676** |
| Recall | 0.490 | **0.671** |
| F1 Score | 0.568 | **0.673** |
| ROC AUC | 0.759 | **0.824** |

The analysis identified several important factors associated with rider retention, including:

- Average trip distance
- Trips completed during the first 30 days
- Weekday riding patterns
- Rider and driver ratings
- City
- Ultimate Black membership

---

## Repository Contents

```
Ultimate_Tech_Challenge.ipynb      Complete analysis notebook
logins.json                        Login timestamp dataset
ultimate_data_challenge.json       Rider retention dataset
README.md                          Project overview
```

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Key Takeaways

This project demonstrates an end-to-end data science workflow by combining exploratory data analysis, experimental design, predictive modeling, and business interpretation. Beyond developing accurate predictive models, the analysis focuses on translating model results into practical recommendations that could help improve customer retention and support data-driven decision making.