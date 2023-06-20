# Cardiac Condition Predictor
Machine Learning Classification Model based on the Decision Tree Algorithm using UCI Heart Disease Dataset.

## Objective
The primary goal of this project is to utilize patient attributes to predict whether an individual has a heart condition. Additionally, we aim to gain insights from the dataset that can aid in comprehending the problem better.

## Dataset Overview
The dataset utilized in this project is multivariate, containing a variety of distinct mathematical or statistical variables for analysis. It consists of 606 rows and 16 columns.

### Column Definitions

- **Age**: Age of the patient in years.
- **Gender**: Gender of the patient (Male/Female).
- **Chest Pain Type (cp)**: [Typical Angina, Atypical Angina, Non-anginal, Asymptomatic].
- **Resting Blood Pressure (trestbps)**: Blood pressure at rest (in mm Hg on admission).
- **Serum Cholesterol (chol)**: Serum cholesterol level in mg/dl.
- **Fasting Blood Sugar (fbs)**: Fasting blood sugar level (> 120 mg/dl).
- **Resting Electrocardiographic Results (restecg)**: [Normal, ST-T Abnormality, LV Hypertrophy].
- **Maximum Heart Rate (thalach)**: Maximum heart rate achieved.
- **Exercise-Induced Angina (exang)**: Presence of exercise-induced angina (True/False).
- **ST Depression (oldpeak)**: ST depression induced by exercise relative to rest.
- **Slope of the Peak Exercise ST Segment (slope)**.
- **Number of Major Vessels (ca)**: Number of major vessels colored by fluoroscopy (0-3).
- **Thalassemia Type (thal)**: [Normal, Fixed Defect, Reversible Defect].
- **Target**: Predicted attribute (presence of heart disease).

## Algorithm: Decision Tree
A decision tree is a supervised learning algorithm that employs a tree-like structure to make predictions based on input data. It partitions data into branches and assigns outcomes to leaf nodes.

Decision trees are employed for classification and regression tasks, producing accurate, efficient, and easily interpretable models.

## Language and Libraries
- **Language**: Python 3.11.4
- **Library**: scikit-learn (sklearn)

This project aims to construct a model that aids in identifying cardiac conditions using patient attributes, showcasing the efficacy and interpretability of the decision tree algorithm.
