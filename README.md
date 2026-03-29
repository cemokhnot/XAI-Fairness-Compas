# XAI-Fairness-Compas

# Overview
This project investigates fairness, bias, and robustness in machine learning using explainable AI (XAI) methods.

Apply:
- SHAP (feature attribution)
- Counterfactual explanations (DiCE)

# Research Question
Can explanation methods reveal racial bias in a recidivism prediction model and how robust are these explanations under small input perturbations?

# Dataset
COMPAS dataset (ProPublica):
https://github.com/propublica/compas-analysis

# Methods
- SHAP (feature importance, global + local explanations)
- Counterfactual explanations (DiCE)

# Installation

Install required packages:

pip install -r requirements.txt


# Usage

Run the notebook:

jupyter notebook notebook.ipynb

# Methods
- Train Random Forest model
- Generate SHAP explanations
- Generate counterfactual explanations (DiCE)
- Evaluate robustness of explanations

#Author
[Anastasios Savvidis]


