# Machine Learning for Brittle-Ductile Material Classification

## Overview

This project explores the use of machine learning to classify materials as **brittle or ductile** based on their mechanical properties. It combines materials science with Python-based data analysis to investigate how mechanical properties can help predict material behavior.

The project aims to demonstrate how data-driven methods can support material classification and contribute to computational materials science research.

## Objectives

* Explore the relationship between mechanical properties and material behavior.
* Develop a machine learning model to classify materials as brittle or ductile.
* Apply data analysis and preprocessing techniques to materials science data.
* Evaluate model performance using appropriate classification metrics.
* Explore the potential of machine learning in computational materials science.

## Features Used

The model uses mechanical properties relevant to material classification, including:

* **Bulk Modulus:** A measure of a material's resistance to uniform compression.
* **Shear Modulus:** A measure of a material's resistance to shear deformation.
* **Poisson's Ratio:** Describes the relationship between transverse and axial strain.
* **Pugh's Ratio:** The ratio of bulk modulus to shear modulus, commonly used as an indicator of ductile or brittle behavior.

These properties provide the input features for investigating the relationship between a material's mechanical characteristics and its classification.

## Methodology

The project follows a machine learning workflow:

1. **Data Preparation:** Load the dataset and inspect the available material properties.
2. **Data Preprocessing:** Prepare the input features and target labels for model training.
3. **Feature Selection:** Use selected mechanical properties as model inputs.
4. **Model Training:** Train a classification model using Logistic Regression.
5. **Model Evaluation:** Assess the model using suitable classification metrics.
6. **Result Analysis:** Examine the model's predictions and consider the physical meaning of the selected features.

The implementation and analysis are provided in the Jupyter Notebook.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Applications

Machine learning approaches to material classification may help researchers:

* Investigate relationships between mechanical properties and material behavior.
* Analyze materials datasets more efficiently.
* Develop data-driven approaches for preliminary material screening.
* Explore computational methods for materials discovery and design.

## Limitations and Future Work

The predictive performance of a model depends on the quality of the dataset, the selected features, and the evaluation method.

Future improvements could include:

* Comparing Logistic Regression with other classification algorithms.
* Improving data preprocessing and feature analysis.
* Using cross-validation and independent test data for more reliable evaluation.
* Investigating feature importance and the physical relationships between mechanical properties.
* Testing the model on additional materials to assess its generalization.

Because Pugh's ratio is calculated from the bulk and shear moduli, these features are mathematically related. Their influence on model performance should therefore be examined carefully to avoid misleading conclusions.

## Conclusion

This project provides an introduction to applying machine learning in materials science. By combining mechanical properties, Python programming, and classification methods, it explores a computational approach to understanding and predicting brittle–ductile material behavior.

