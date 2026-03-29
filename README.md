# XAI-Fairness-Compas

# Overview
This project investigates fairness, bias, and robustness in machine learning using explainable AI (XAI) methods.

The focus is about recidivism prediction based on the COMPAS data, which is a high-stakes application where biased predictions can be deadly.

We analyze:
- Whether the model uses sensitive attributes such as race
- Whether explanations are stable under small input changes


# Research Question
Can explanation methods reveal racial bias in a recidivism prediction model and how robust are these explanations under small input perturbations?

# Methods
- SHAP (feature importance, global + local explanations)
- Counterfactual explanations (DiCE)

# Installation

Install required packages:

pip install -r requirements.txt


# Usage

Run the notebook:

jupyter notebook notebook.ipynb

#Author
[Anastasios Savvidis]


