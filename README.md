# Gold Ore Purification — ML Recovery Prediction

## Overview
Developed ML models to predict gold recovery efficiency at rougher and final purification stages of industrial ore processing. Evaluated using sMAPE metric with cross-validation.

## Tools & Technologies
Python · Scikit-learn · Pandas · NumPy · EDA · Cross-validation · sMAPE

## Key Results
- Verified the rougher recovery formula numerically against the dataset's own values
- Found and excluded features that leak the target (outputs measured after the stage being predicted)
- Compared models on weighted sMAPE (25% rougher stage, 75% final stage); validation scores ranged from about 8.9% to
  14.9% across the models tried
- **Final weighted sMAPE on the held-out test set: about 13.6%** (random forest)

## How to Run
Open `gold_project.ipynb` in Jupyter Notebook or JupyterLab.
