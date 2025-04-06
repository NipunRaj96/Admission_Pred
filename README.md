# Graduate Admission Prediction

## 📌 Project Overview

This project focuses on predicting graduate admission chances using a deep learning model. The dataset contains various features related to a student's profile, such as GRE Score, TOEFL Score, CGPA, and more. The objective is to build a regression model that predicts the probability of admission (between 0 and 1).

## 🚀 Technologies Used

* Python  
* Pandas & NumPy  
* Matplotlib  
* Scikit-learn  
* TensorFlow / Keras 

## 🧠 Model Description

The project compares two models:

Provided Base Model – Accuracy: **80.7%**

Custom Deep Learning Model – Accuracy: **81.4%**

### The custom model includes:

* Input layer matching the number of features

* One or more hidden layers with ReLU activation

* Output layer with linear activation (for regression)

* Mean Squared Error (MSE) as the loss function

## 📊 Evaluation Metrics

R² Score: Evaluates how well predictions approximate the actual values. Higher is better (max is 1.0).

Mean Squared Error (MSE): Measures the average squared difference between predictions and true values. Lower is better.

## 🧪 Results

The deep learning model achieved slightly better performance than the baseline model. This highlights the potential of neural networks in regression problems, even with small datasets.

## ✅ Future Improvements

* Hyperparameter tuning
* Model regularisation
* Cross-validation for better evaluation
* Deploying model as a web app 

## ✨ Credits

Created with guidance from **Nitish Singh** and beginner-friendly resources to understand deep learning in real-world applications.
