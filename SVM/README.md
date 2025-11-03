# Cancer_prediction_using_SVM
🧠 Breast Cancer Classification using Support Vector Machines (SVM)  This project demonstrates the use of Support Vector Machine (SVM) models for classifying breast cancer tumors as Malignant (M) or Benign (B) using the Breast Cancer Wisconsin dataset. 
🚀 Project Overview

The dataset is preprocessed, scaled, and split into training and testing sets.
Three different SVM kernels — Linear, Polynomial, and RBF (Radial Basis Function) — are implemented and compared based on their performance metrics.

🧩 Steps Involved
Data Loading & Exploration:
Read the dataset using pandas.
Display initial rows and dataset information.
Check class distribution in the target variable (diagnosis).
Data Cleaning:
Removed unnecessary columns like id and Unnamed: 32.
Feature Scaling:
Applied StandardScaler to normalize feature values.
Data Splitting:
Split dataset into 80% training and 20% testing data using train_test_split.
Model Training:
Trained three SVM models with different kernels: linear, polynomial, and rbf.
Model Evaluation:
Evaluated models using:
Accuracy Score
Confusion Matrix
Classification Report
Confusion Matrix Visualization

📊 Libraries Used
pandas – for data handling
scikit-learn (sklearn) – for preprocessing, modeling, and evaluation

⚙️ Results
Each model’s performance is printed and visualized, allowing comparison of how different SVM kernels handle the same dataset.

🏁 Conclusion
This project provides insight into how SVMs can effectively classify medical data and how kernel selection impacts model performance.
