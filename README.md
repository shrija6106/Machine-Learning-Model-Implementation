Machine Learning Model Implementation

This project is part of CODTECH Internship Task-4. The goal is to build a predictive machine learning model using scikit-learn.

📌 Project Overview

Dataset: Breast Cancer (from scikit-learn)

Algorithm: RandomForestClassifier

Objective: Classify tumors as Malignant or Benign

Deliverable: Jupyter Notebook with implementation & evaluation

⚙️ Features

Data Preprocessing & Scaling

Model Training & Testing

Accuracy, Classification Report, Confusion Matrix

ROC Curve & AUC Score

Feature Importance Visualization

Model saved with joblib

▶️ Run Instructions
# Clone repo
git clone https://github.com/your-username/codtech-task4-ml.git
cd codtech-task4-ml

# Create environment
python -m venv codtech_env
source codtech_env/bin/activate      # Mac/Linux
codtech_env\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook task4_ml_model.ipynb

📂 Files

task4_ml_model.ipynb → Main Notebook

breast_cancer_rf_model.pkl → Saved Model

requirements.txt → Dependencies
