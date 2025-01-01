# TitanicSurvivalPrediction
This project focuses on predicting passenger survival on the Titanic using the Kaggle Titanic Survival dataset. The dataset includes demographic, socio-economic, and travel details of passengers.
The goal is to predict whether a passenger survived the disaster (binary classification: survived or not survived) based on the given features.

Several machine learning models were implemented and evaluated for performance:
* Logistic Regression
* Decision Tree
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest
* LightGBM

Each model was assessed based on the following metrics:
* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

Summary of Results
* Random Forest achieved the highest accuracy (84.36%) and demonstrated robust overall performance.
* LightGBM exhibited the best ROC-AUC score (0.89), indicating excellent discriminatory ability.
* Logistic Regression provided a good balance of simplicity and accuracy (78.77%), making it suitable for scenarios requiring interpretability.
* KNN and SVM performed well with accuracy scores exceeding 82%, offering reliable predictions.
* Decision Tree was effective with an accuracy of 81.01% and high recall for positive cases.

This project demonstrates the application of machine learning techniques to real-world classification problems, with Random Forest and LightGBM emerging as the most effective models for predicting survival on the Titanic.


