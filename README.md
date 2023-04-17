# EEP_596_Project1

### Stress Level Prediction using Heart Rate Variability and Machine Learning
The primary objective of this project is to develop a model that can accurately predict stress levels based on various features of heart rate variability (HRV) using machine learning techniques. This repository contains Project 1 for the course EE P 596: Advanced Introduction to Machine Learning. The project, instructed by Prof. Karthik Mohan, Student: Naif A Ganadily, TA: Ayush Singh, Grader: Fatwir SM.

### Project Overview
The project is structured in several stages, including data normalization, feature extraction, model implementation, evaluation, and feature importance analysis. I have implemented and compared the following classification algorithms:

1. Decision Tree (DT)

2. Adaboost (ADA)

3. Random Forest with Randomized Search

4. Random Forest with Grid Search

### Data Normalization and Feature Extraction
During the data normalization stage, I independently normalized the input data frames, df and df2, scaling all the values of the feature column to the range of 0 to 1. The top features are selected using SelectKBest with f_classif, and feature pairs are ranked using cross-validation with the Decision Tree model.

### Model Implementation and Evaluation
To train and evaluate the performance of different models, I used the preprocessed dataset. I assessed each model's performance using various metrics, such as precision, recall, F1-score, and accuracy. However, none of the models perform exceptionally well, as the best score values are relatively low.

### Feature Importance Analysis
By employing a cross-validation approach, I ranked feature pairs based on their average cross-validation score when used in the Decision Tree model. This step enhances the understanding of feature importance and can help guide further improvements to the models.

### Key Competencies
This project highlights my expertise in:

* Data normalization and feature extraction for machine learning
* Implementing and evaluating various machine learning algorithms
* Model selection and hyperparameter tuning
* Analyzing feature importance for interpretability and model improvement
* Effective presentation of results and performance metrics
