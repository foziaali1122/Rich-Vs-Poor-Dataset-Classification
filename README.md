Rich vs Poor Classification
📌 Overview

This project explores the challenge of predicting whether an individual is Rich or Poor using a high-dimensional dataset. By analyzing demographic, educational, and socio-economic features, we apply multiple machine learning models to uncover the best approach for accurate income classification.


---


📊 Dataset Description

Rows: 22,792

Columns: 16

Target Variable: Predictions (Rich / Poor)

Features include:

Age, Education & Education-num

Marital Status & Occupation

Relationship Role, Gender, Race

Capital Gain / Loss, Hours per Week

Native Country & ID

These features provide valuable insights into how personal and socio-economic factors contribute to wealth inequality.

---


🤖 Models Applied

Logistic Regression

Gaussian Naive Bayes

Decision Tree

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Random Forest


---



🏆 Model Accuracy Comparison
Model	Accuracy (%)
Logistic Regression	69.09%
Gaussian Naive Bayes	62.77%
Decision Tree	84.93%
K-Nearest Neighbors	70.84%
Support Vector Machine	58.87%
Random Forest ⭐	88.81%

---


📌 Conclusion: Random Forest outperformed all models, making it the most reliable choice for this classification task.

📷 Visualizations

Countplots for categorical features

Scatter plots for numerical features vs target

Bar & Pie charts for model accuracy comparison

---
