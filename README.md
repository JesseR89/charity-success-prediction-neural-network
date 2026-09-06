# Charity Success Prediction Using Neural Networks

## Overview

This project develops a deep learning classification model to predict whether organizations receiving funding are likely to be successful.

Using historical applicant and funding data, a neural network was built with TensorFlow and Keras to identify patterns associated with successful outcomes.

The project demonstrates an end-to-end machine learning workflow including data preprocessing, feature engineering, neural network development, model training, and performance evaluation.

## Business Objective

Organizations that distribute funding must evaluate large numbers of applicants while determining which opportunities are most likely to produce successful outcomes.

Predictive modeling can supplement this decision-making process by identifying patterns in historical data and estimating the probability of success for future applicants.

The objective of this project is to develop a binary classification model that predicts whether an applicant will be successful based on organizational and funding characteristics.

## Data Preparation

The dataset contains information describing funding applicants and their characteristics.

The target variable is:

**`IS_SUCCESSFUL`**

Applicant characteristics are used as model features.

Preprocessing included:

* Removing unnecessary identification fields
* Analyzing categorical variables
* Grouping low-frequency categories
* Encoding categorical variables
* Separating features and target variables
* Creating training and testing datasets
* Scaling numerical features

## Neural Network Architecture

The predictive model was developed using **TensorFlow and Keras**.

The neural network uses:

* Input features derived from the processed applicant dataset
* Multiple dense hidden layers
* **ReLU** activation functions in the hidden layers
* **Sigmoid** activation for binary classification

The model was trained across multiple epochs to learn relationships between applicant characteristics and successful funding outcomes.

## Model Performance

During training, the neural network achieved approximately **73–74% accuracy**.

This indicates that the model was able to identify meaningful patterns within the applicant data, while also leaving room for additional model optimization.

## Technologies

* Python
* Pandas
* TensorFlow
* Keras
* Scikit-learn
* NumPy
* Jupyter Notebook

## Skills Demonstrated

* Deep learning
* Neural networks
* Binary classification
* Data preprocessing
* Categorical encoding
* Feature scaling
* Train/test validation
* TensorFlow and Keras
* Model performance evaluation

## Business Applications

Similar classification approaches can be applied to business problems such as:

* Funding and investment screening
* Credit-risk assessment
* Customer conversion prediction
* Applicant scoring
* Operational risk analysis
* Resource allocation

Machine learning models should supplement rather than replace human judgment, particularly when predictions influence financial or organizational decisions.

## Limitations & Future Improvements

Model performance could potentially be improved through additional experimentation with:

* Neural network architecture
* Number of hidden layers and neurons
* Activation functions
* Feature selection
* Hyperparameter tuning
* Regularization
* Alternative classification algorithms

Comparing the neural network against simpler baseline models such as logistic regression or random forests would also help determine whether the additional complexity of deep learning produces meaningful predictive improvements.

## Conclusion

This project demonstrates the development of an end-to-end neural network classification workflow using TensorFlow and Keras.

The model achieved approximately **73–74% training accuracy** while demonstrating how deep learning techniques can be applied to organizational and funding data to support predictive decision-making.
