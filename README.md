🧠 Performance Evaluation of Machine Learning Models for Brain Disease Prediction
📌 Project Overview

This repository contains the complete experimental work conducted as part of our academic research paper titled:

“Performance Evaluation of AI Models for Multi-Class Brain Disease Prediction” 

Brain_Disease (2)

The project evaluates and compares multiple Machine Learning models for predicting three brain-related diseases:

Depression

Alzheimer’s Disease

Brain Stroke

The emphasis is on model comparison, metric-based evaluation, and result visualization, which are critical in healthcare-related ML applications.

🧠 Why This Project Is Relevant 

Demonstrates end-to-end Machine Learning workflow

Shows ability to work on healthcare / medical datasets

Focuses on model evaluation, not just training

Addresses class imbalance and metric interpretation

Backed by formal research work

Uses clear visualizations for technical communication

🎯 Problem Statement

In medical Machine Learning, relying solely on accuracy can be misleading.
This project aims to evaluate multiple ML classifiers using diverse performance metrics and visual analysis to identify the most reliable models for brain disease prediction.

🧪 Datasets

Publicly available CSV datasets were used for:

Depression

Alzheimer’s Disease

Brain Stroke

Each dataset contains patient demographic and clinical attributes with binary class labels (0/1).

🤖 Machine Learning Models Used

The following supervised learning models were implemented and compared:

Logistic Regression (LR)

Support Vector Machine (SVM)

Random Forest (RF)

Naive Bayes (NB)

Gradient Boosting (XGBoost)

Linear Discriminant Analysis (LDA)

📊 Evaluation Metrics

Models were evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

ROC–AUC Curve

This multi-metric evaluation ensures reliable performance assessment, especially for imbalanced datasets such as Brain Stroke.

📈 Visualization

All experimental results were visualized using Matplotlib, including:

Metric comparison bar graphs

Heatmaps for model performance analysis

Disease-wise performance comparison plots

These visualizations help interpret strengths and weaknesses of each model clearly.

🔍 Key Insights

Depression: Logistic Regression and Gradient Boosting achieved near-perfect performance

Alzheimer’s Disease: Ensemble models (Gradient Boosting, Random Forest) showed the most balanced results

Brain Stroke: Highlighted the importance of recall and precision over accuracy alone

Overall, ensemble-based models consistently outperformed traditional classifiers.

🛠️ Tech Stack

Python

Scikit-learn

Pandas, NumPy

Matplotlib

Jupyter Notebook

🤝 Contributors

Shubham Kumar

Aakriti Khanna

📄 Research Context

This repository represents the implementation, experimentation, evaluation, and visualization work carried out for our research paper, ensuring reproducibility and practical insight into the research methodology.
