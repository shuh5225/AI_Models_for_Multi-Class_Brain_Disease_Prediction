🧠 Performance Evaluation of Machine Learning Models for Brain Disease Prediction
📌 Overview

This repository contains the complete experimental and analytical work conducted as part of our research paper titled:

“Performance Evaluation of AI Models for Multi-Class Brain Disease Prediction” 

Brain_Disease (2)

The project focuses on evaluating and comparing multiple Machine Learning models for predicting three critical brain diseases:

Depression

Alzheimer’s Disease

Brain Stroke

The objective was to identify the most reliable models for medical prediction tasks by analyzing multiple performance metrics and visualizing results using clear, interpretable graphs.

💡 Why This Project Matters (Recruiter View)

Demonstrates end-to-end ML workflow (data → preprocessing → modeling → evaluation → visualization)

Shows understanding of medical ML challenges like class imbalance

Applies model comparison and performance analysis, not just training

Emphasizes interpretability and evaluation rigor, critical in healthcare AI

Represents published academic research work, not a toy project

🎯 Problem Statement

Accuracy alone is insufficient for evaluating Machine Learning models in healthcare applications.
This project aims to compare multiple ML classifiers across different brain disease datasets using robust evaluation metrics and visual analysis to support informed model selection.

🧪 Datasets

Publicly available CSV datasets (sourced from Kaggle) were used for:

Depression

Alzheimer’s Disease

Brain Stroke

Each dataset includes patient demographic and clinical attributes with binary class labels (0/1) indicating disease presence.

🤖 Models Implemented

The following supervised Machine Learning models were trained and evaluated for each disease:

Logistic Regression (LR)

Support Vector Machine (SVM)

Random Forest (RF)

Naive Bayes (NB)

Gradient Boosting (XGBoost)

Linear Discriminant Analysis (LDA)

📊 Evaluation Metrics

To ensure reliability in a medical context, the models were evaluated using:

Accuracy

Precision

Recall (Sensitivity)

F1-Score

Confusion Matrix

ROC–AUC Curve

This approach highlights scenarios where high accuracy can still mask poor recall, especially in the Brain Stroke dataset.

📈 Visualization

All results were visualized using Matplotlib for interpretability:

Disease-wise bar graphs for metric comparison

Heatmaps to analyze model performance correlations

Comparative plots to highlight strengths and weaknesses of each classifier

🔍 Key Results (High-Level)

Depression: Logistic Regression and Gradient Boosting achieved near-perfect performance

Alzheimer’s Disease: Gradient Boosting and Random Forest showed the most balanced metrics

Brain Stroke: Ensemble models performed best, revealing limitations of accuracy-only evaluation

Overall, ensemble techniques consistently outperformed traditional classifiers, reinforcing their suitability for healthcare ML applications.

🛠️ Tech Stack

Programming: Python

Libraries: Scikit-learn, Pandas, NumPy

Visualization: Matplotlib

Environment: Jupyter Notebook

🤝 Contributors

Shubham Kumar

Aakriti Khanna

📄 Research Context

This repository represents the practical implementation, experimentation, and analysis conducted for our research paper, including:

model training

metric evaluation

result visualization

comparative analysis

It is intended to provide transparency, reproducibility, and hands-on insight into the research work.
