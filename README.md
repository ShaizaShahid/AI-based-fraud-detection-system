🧠 Credit Card Fraud Detection – AI/ML Project

📌 Project Overview

This project detects fraudulent credit card transactions using machine learning models. Multiple models were trained including Logistic Regression, Random Forest, and XGBoost. The best-performing model (XGBoost) was selected for final evaluation and real-time simulation.


⚙️ Setup Instructions

Extract the project folder

Install required libraries:

pip install -r requirements.txt

Open notebook.ipynb in VS Code or Jupyter

Run cells step by step


▶️ How to Run Project

Load dataset (creditcard.csv)

Run preprocessing (train-test split, SMOTE, scaling)

Train models (LR, RF, XGBoost)

Evaluate performance

Run SHAP explainability

Run streaming simulation (Step 8)


🤖 Model Details

Models used:


Logistic Regression

Random Forest

XGBoost (Best Model)



Final model is saved as:

trained_model.pkl


📚 Libraries Used

pandas

numpy

scikit-learn

xgboost

imbalanced-learn

shap

joblib

matplotlib


⚠️ Challenges Faced

Highly imbalanced dataset

Risk of data leakage

Model overfitting on minority class

Complexity in interpreting results


🚀 Future Improvements

Deploy model using FastAPI or Flask

Improve real-time fraud detection system

Add advanced feature engineering

Handle concept drift in production


📊 Explainable AI (SHAP)

SHAP was used to interpret model predictions:

Individual prediction explanation (waterfall plot)

Global feature importance (summary plot)

Feature impact analysis (bar plot)


📡 Streaming Simulation

A batch-based streaming system was implemented to simulate real-time fraud detection. Transactions were processed in batches and predictions were generated continuously using the trained model.

📁 Project Structure

StudentName_AI_ML_Advanced_Task/

│

├── notebook.ipynb

├── report.pdf

├── requirements.txt

├── fixed_pipeline.py

├── trained_model.pkl

├── README.md

└── deployment/
