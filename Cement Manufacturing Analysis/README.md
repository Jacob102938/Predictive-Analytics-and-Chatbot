# Cement_Manufacturing.ipynb — Cement Strength Prediction
## Introduction
A machine learning study to predict the compressive strength of cement based on its mix composition.
## Dataset Used
Cement_Manufacturing.csv — contains ingredient proportions and resulting cement strength.
## Variables

Dependent: strength (compressive strength of cement)
Independent: Cement ingredients (e.g., clinker, slag, fly ash, water, superplasticizer, coarse/fine aggregate, age)

## Key Insights

A Random Forest Regressor was used, achieving an R² of ~0.91, meaning 91% of strength variance is explained by the model.
MAE of ~3.28 indicates predictions are close to actual values.
Feature importance analysis revealed that certain ingredients (likely age and water ratio) have a disproportionately higher influence on strength.

## Conclusion
Random Forest is a highly effective model for predicting cement strength. The results can help manufacturers optimize mix compositions to achieve desired strength targets, reducing material waste and cost.
