# Online-Payment-Fraud-Detection-using-Machine-Learning

📌 Project Overview
This project focuses on detecting fraudulent online payment transactions using machine learning techniques. The dataset is highly imbalanced, and the goal is to build a model that minimizes false negatives (frauds classified as genuine).

🗂 Dataset

Source: Kaggle – Credit Card Fraud Detection Dataset

Total records: ~285,000 transactions

Features: Transaction details (Time, Amount, anonymized features V1–V28)

Target: 0 = Genuine, 1 = Fraud

⚙️ Project Workflow

Data Preprocessing

Missing value handling

Feature scaling with StandardScaler

Train-test split

Handling Class Imbalance

Applied SMOTE (Synthetic Minority Oversampling Technique)

Model Training

Logistic Regression

Random Forest Classifier

XGBoost / LightGBM

Evaluation Metrics

Confusion Matrix

Precision, Recall, F1-Score

ROC-AUC Curve

Deployment

Built a Streamlit app for real-time fraud detection

User can upload transaction data (CSV) and get fraud prediction instantly

🛠️ Tech Stack

Python (Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn)

Streamlit (for web app)

Jupyter Notebook

📊 Results

Best performing model: Random Forest (with SMOTE)

Recall (Fraud class): ~92%

ROC-AUC: ~0.98
