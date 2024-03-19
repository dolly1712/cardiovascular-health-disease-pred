# Alma Better Capstone Project

# Ten-Year Cardiovascular Disease (CHD) Prediction

# Overview
This project focuses on predicting the ten-year risk of cardiovascular disease (CHD) for individuals based on various risk factors. Cardiovascular disease is a leading cause of mortality worldwide, and early identification of individuals at high risk is crucial for prevention and timely intervention. By leveraging machine learning techniques, this project aims to develop predictive models that can accurately estimate an individual's probability of developing CHD within the next ten years.

# Table of Contents
1. Motivation
2. Data
3. Methodology
4. Usage
5. Results
6. Contributing

# Motivation
Cardiovascular disease poses a significant public health challenge globally, and proactive risk assessment is essential for effective prevention strategies. Predictive models for CHD risk can assist healthcare professionals in identifying high-risk individuals and implementing personalized interventions to reduce the burden of cardiovascular morbidity and mortality.

# Data
The dataset used in this project comprises clinical and demographic information from individuals, including age, gender, blood pressure, cholesterol levels, smoking status, and family history of CHD. This dataset is utilized to train and evaluate the predictive models for estimating the ten-year risk of CHD.

# Methodology
Various machine learning algorithms, such as logistic regression, support vector machines, random forests, and gradient boosting, are employed to develop predictive models for CHD risk prediction. The models are trained on a subset of the data and evaluated using appropriate performance metrics, including accuracy, sensitivity, specificity, and area under the receiver operating characteristic curve (AUC-ROC).

# Conclusion
1. There are 2917 records and 16 features.
2. There are no duplicate values.
3. All the continuous variables are positively skewed except age (which is almost normally distributed)
4. Majority of the patients belong to the education level 1, followed by 2, 3, and 4 respectively.
5. There are more female patients compared to male patients.
6. The variables 'systolic BP'and 'diastolic BP' are highly correlated.
7. Models we implemented are 'Linear Regression', 'Lasso Regression', 'Ridge Regression', 'Logistic Regression', 'Elastic Net Regression','Decision Tree Classifier', 'Random Forest Classifier', 'Gradient Boosting Classifier', 'KNN Classifier', 'SVC'.
8. Models like Random Forest Classifier(79%) and Gradient Boosting Classifier(75%) exhibit relatively higher accuracy and precision scores on both the training and testing datasets.
9. High Recall means we want to detect as many people as possible who have CHD, even if we accidentally say some healthy people have CHD.
10. High Precision means we want to be very sure that the people we say have CHD actually have CHD, so we don't accidentally treat healthy people.
11. The F1 Score is a way to measure how accurate a model is in finding people having CHD while also being careful not to mistake healthy people as sick. It's like finding a balance between catching as many people having cardiovascular problems as possible and making sure we're correct about who is actually sick..
12. Models with high
      Recall: Random forest classifier
      Precision: Ridge Regression, ElasticNet Regression, Random forest classifier
      F1 score: Random forest classifier

# Results
The developed predictive models demonstrate promising performance in estimating the ten-year risk of cardiovascular disease. Detailed evaluation results, including model performance metrics and visualizations, are provided in the project's Google colab notebook.
