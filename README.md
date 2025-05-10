# Heart Disease Prediction

This project predicts the likelihood of heart disease based on clinical and health parameters using machine learning. It follows a complete data science workflow, from data preprocessing to model evaluation, and is deployed on Hugging Face Spaces for interactive use.

## Project Overview

A supervised learning model is trained to classify whether a person is at risk of heart disease. The project includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Model training and evaluation
* Deployment for public access

## Technologies Used

* Python
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn
* Gradio (for UI)
* Hugging Face Spaces (for deployment)

## Dataset

The dataset includes health-related features such as:

* Age
* Sex
* Chest pain type
* Blood pressure
* Cholesterol
* Fasting blood sugar
* ECG results
* Maximum heart rate
* Exercise-induced angina
* ST depression
* Major vessels
* Thalassemia
* Target (1 = heart disease, 0 = no heart disease)

## Workflow Summary

1. **Data Preprocessing:** Missing values handled, categorical variables encoded, and features scaled.
2. **EDA:** Key patterns visualized to understand feature relationships.
3. **Modeling:** Trained and compared classifiers like Logistic Regression, Random Forest, and KNN.
4. **Evaluation:** Used metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
5. **Deployment:** Built a Gradio interface and deployed on Hugging Face.

## Live Demo

You can try the live app here:
**[Heart Disease Prediction on Hugging Face Spaces](https://huggingface.co/spaces/Husnain572/Heart-Disease-Prediction)
**
