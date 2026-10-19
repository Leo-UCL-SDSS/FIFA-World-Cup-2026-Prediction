# 2026 FIFA World Cup Quarterfinal Prediction

An applied machine learning project using historical football data
to predict quarterfinal qualification in the 2026 FIFA World Cup.

**Author:** Haofan (Leo) Liao  
**Institution:** University of California, Santa Barbara (UCSB)  
**Course:** PSTAT 135  
**Completed:** June 2026  
**Project Type:** Academic Machine Learning Project

## Overview

This project investigates the factors associated with FIFA World Cup
success using supervised and unsupervised machine learning.

The analysis combines team rankings, recent results, squad
characteristics and historical tournament performance.

## Dataset

- 192 historical team-tournament observations (2002–2022)
- 48 observations for 2026 predictions
- 16 predictive features

Data sources include historical FIFA World Cup datasets and
international football Elo ratings.

## Machine Learning Methods

**Supervised learning**
- Decision Tree classification
- Support Vector Machine (SVM)
- Hyperparameter tuning with RandomizedSearchCV
- Stratified five-fold cross-validation

**Unsupervised learning**
- Principal Component Analysis (PCA)
- K-Means clustering

**Model evaluation**
- Accuracy, precision, recall and F1-score
- ROC-AUC and confusion matrices
- External comparison with Elo ratings

## Results

The selected SVM configuration achieved:

| Metric | Result |
|---|---:|
| Accuracy | 84.6% |
| Quarterfinalist recall | 60.0% |
| ROC-AUC | 0.690 |

The model identified Spain, Brazil, France, England and Portugal
among the leading candidates for quarterfinal qualification.

These results reflect the original project's evaluation procedure
and are not independently validated deployment-performance estimates.

## Limitations

The historical dataset contains only 192 observations.

The original analysis used stratified random splitting rather
than chronological tournament-based validation.

Classification thresholds were explored using test-set results,
which can introduce optimistic performance estimates.

Future improvements include chronological validation,
threshold selection on validation data, and comparison with
additional machine learning models.

## Project Files

- `FIFA_World_Cup_2026_Project.ipynb` — Python implementation
- `FIFA_World_Cup_2026_Project.pdf` — Full analytical report

## Technologies

Python, pandas, NumPy, scikit-learn, matplotlib, seaborn.

## Author

**Haofan (Leo) Liao**

Developed at the University of California, Santa Barbara (UCSB)
during my 2025–2026 exchange year.

Home institution: University College London (UCL)  
BSc Social Sciences with Data Science
