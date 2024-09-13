# Explainable AI (XAI) with Iris Dataset

This repository contains a Jupyter Notebook that demonstrates various explainable AI (XAI) techniques using the Iris dataset. The goal is to classify iris species and understand the model's predictions through different interpretability methods.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SHAP
- LIME

## Dataset

The Iris dataset consists of 150 samples of iris flowers, with three species: Setosa, Versicolor, and Virginica. Each sample has four features: sepal length, sepal width, petal length, and petal width.

## Explainability Techniques

- **SHAP (SHapley Additive exPlanations)**: Shows how much each feature contributes to the prediction.
- **LIME (Local Interpretable Model-agnostic Explanations)**: Explains a single prediction by approximating the model locally.
- **PDP (Partial Dependence Plots)**: Displays how a feature affects the prediction, ignoring other features.
- **Feature Importance**: Ranks features by their influence on the prediction.

## Model

The notebook uses a RandomForestClassifier, an ensemble learning method that builds multiple decision trees and combines their results to improve accuracy and reduce overfitting. Using 100 trees means the model averages the predictions of 100 different trees, making it more robust and stable.

## Results

The notebook provides visualizations and explanations for the model's predictions using the above techniques.

