Data Science & Machine Learning Projects 

Welcome to my repository of end-to-end Data Science and Machine Learning projects. 

Repository Structure & Projects Overview

This repository is organized into distinct project directories, each targeting a specific business or clinical objective:

1. Diabetes Risk Prediction & Advanced EDA (Diabetes Risk Prediction.ipynb & Diabetes.ipynb)
Objective: Predict binary diabetes risk profiles using behavioral, clinical, and physiological patient indicators.

Datasets Used: Behavioral Risk Factor Surveillance System (BRFSS 2015) and Healthcare Diabetes datasets.

Key Implementation Highlights:

Automated Profiling: Generated deeply granular, interactive exploration profiles using ydata_profiling (ProfileReport) and sweetviz to isolate feature interactions, missing values, and variance anomalies.

Algorithmic Evaluation: Built and optimized classification engines using Support Vector Classifiers (SVC), Random Forests, Logistic Regression, and Decision Trees.

Unsupervised Learning: Applied K-Means Clustering to segment patient records based on core health variables and evaluated performance with specialized tracking matrices (e.g., maximizing Recall and F1-scores for the high-risk diabetic class).

Pipeline Operations: Implemented data dimensionality reduction via Principal Component Analysis (PCA), continuous variable normalization via StandardScaler, and hyperparameter tuning with GridSearchCV.


2. Bank Marketing Campaign Optimization 
Objective: Maximize institutional conversion rates by predicting whether a targeted client will subscribe to a long-term financial deposit product.

Dataset Used: Bank Client Demographic and Marketing Campaign History dataset.

Key Implementation Highlights:

Data Cleansing: Implemented data processing routines to manage mixed categorical types (e.g., employment, marital status, education) and continuous campaign timelines.

Comparative Classification: Built comparative modeling frameworks across K-Nearest Neighbors (KNN), Support Vector Machines (SVM), and Naive Bayes.

Performance Metrics: Conducted deep-dive classification matrix reviews, finding that while KNN balanced precision and recall effectively, SVM achieved the highest overall reliability for both classes (e.g., 0.88 precision for non-subscribers).


pip install pandas numpy matplotlib seaborn scikit-learn ydata-profiling sweetviz
Open any of the .ipynb notebooks inside Jupyter to walk through the step-by-step logic, pipeline configurations, and final classification charts.
