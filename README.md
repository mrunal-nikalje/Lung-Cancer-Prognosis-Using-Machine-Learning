# Lung-Cancer-Prognosis-Using-Machine-Learning
Comparative analysis of ML classifiers for lung cancer detection with optimized Logistic Regression (MLR) using threshold tuning (0.8 &amp; 0.4) to improve accuracy.


## Overview

This project focuses on predicting lung cancer using multiple Machine Learning algorithms and comparing their performance to identify the most accurate model.

The project goes beyond basic prediction by:

Comparing different classification algorithms
Identifying the best-performing model (Logistic Regression)
Improving its performance using a Modified Logistic Regression (MLR) approach with custom threshold tuning


## Key Idea of the Project

Unlike traditional ML projects that use a single model, this project:

- Compares multiple algorithms
- Selects the best-performing model based on accuracy
- Enhances the selected model using threshold optimization


## Final Outcome:

Logistic Regression performed best among all algorithms
Further improvement was achieved using Modified Logistic Regression (MLR)
Custom thresholds (0.8 and 0.4) were applied to improve prediction accuracy


## Algorithms Used

The following Machine Learning algorithms were implemented and compared:

Logistic Regression  (Best Performing)
Decision Tree
Ada Boost
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Naive Bayes 
Neural Network
### MLR-Modified Logistic Regression 


## Model Optimization using Threshold Tuning (Core Innovation)

The primary contribution of this project is improving the performance of the best model, Logistic Regression.
In this project, a Modified Logistic Regression (MLR) approach is introduced.
Custom decision thresholds of 0.8 and 0.4 are applied instead of the default value.
These thresholds help in better handling borderline prediction cases.
Improves the balance between sensitivity (recall) and specificity.
Reduces misclassification errors in predictions.
Results in an increase in overall model accuracy.
Demonstrates that threshold tuning is an effective optimization technique without adding model complexity.


## Results 

In this project, multiple Machine Learning algorithms were implemented and evaluated to identify the most effective model for lung cancer prediction. After training and testing all models, it was observed that Logistic Regression achieved the highest accuracy of approximately 88%, making it the best-performing baseline model among all the algorithms used.

Other models such as KNN , SVM, Decision Tree and Neural Network achieved around 84% accuracy, while Ada Boost gave 85% and Naive Bayes gave approximately 86% accuracy.

From these results, it is clear that although some advanced algorithms like Decision Tree and SVM are powerful, they did not outperform Logistic Regression for this particular dataset. This suggests that the dataset follows a relatively linear pattern, which is better captured by Logistic Regression.



###After Optimization:

Modified Logistic Regression (MLR) achieved improved accuracy compared to standard Logistic Regression
Threshold tuning significantly enhanced prediction performance

## Conclusion

This project highlights the importance of algorithm comparison and model optimization in Machine Learning. By applying threshold tuning to Logistic Regression, the model’s performance was significantly improved, demonstrating that even simple models can outperform complex ones when properly optimized.
