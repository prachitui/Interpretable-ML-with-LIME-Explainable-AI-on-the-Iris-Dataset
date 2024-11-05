# Interpretable ML with LIME: Explainable AI on the Iris Dataset

## Overview
This project demonstrates the use of Explainable AI (XAI) techniques to enhance transparency and interpretability in machine learning models. By training a Random Forest classifier
on the Iris dataset and applying LIME (Local Interpretable Model-agnostic Explanations), this project provides feature-based insights into model predictions, showcasing how XAI can make 
complex models more understandable and trustworthy.

## Project Objectives
1. **Train a Classifier**: Build a Random Forest model to classify iris species based on sepal and petal measurements.
2. **Apply Explainability with LIME**: Use LIME to generate human-interpretable explanations for the model's predictions, focusing on which features most influence each prediction.
3. **Enhance Transparency and Trust**: Demonstrate the importance of XAI in promoting model interpretability, fairness, and debugging.

## Dataset
The [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris), a classic dataset in machine learning, contains:
- 150 samples of iris flowers.
- 4 features: sepal length, sepal width, petal length, and petal width.
- 3 target classes representing iris species: Setosa, Versicolor, and Virginica.

## Project Steps
1. **Data Loading and Exploration**: Load and explore the Iris dataset, examining the distribution of each feature and its relationship to the target classes.
2. **Model Training**: Train a Random Forest classifier, leveraging ensemble learning to achieve robust performance in species classification.
3. **Model Evaluation**: Assess the model's accuracy to ensure reliable predictions.
4. **Explain Predictions with LIME**: Use LIME to generate explanations for specific predictions, identifying key features that drive the model's decisions.
5. **Visualization of Explanations**: Visualize LIME’s output to show the influence of features like petal length and sepal width on model predictions.

## Results
The project achieved high classification accuracy and successfully used LIME to interpret the predictions. LIME’s feature-based explanations provided insights into the importance of
specific attributes, promoting model transparency, interpretability, and user trust.

## Key Files
- **xai-on-iris-dataset.ipynb**: Jupyter Notebook with the full implementation, including data loading, model training, evaluation, and explanation generation using LIME.



