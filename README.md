# Project:
- Payment Fraud Detection using Machine Learning
  ![Payment-Fraud-Detection_Overgraph](https://github.com/user-attachments/assets/6695919e-22be-4ef6-9f5e-75c47fc0e7b7)
# Objective
- The objective of this project is to detect fraudulent transactions in online payments using machine learning classification techniques. The aim is to build a model that can identify suspicious transactions and reduce risks for financial institutions, merchants, and customers.
# Why We Use This Project
- Business Use Case: Fraudulent transactions cost businesses and banks billions every year. Early detection helps in preventing financial loss and protecting customers.
- Data Science Perspective: This is a binary classification problem (Fraud vs Non-Fraud) with imbalanced data, making it an excellent use case for supervised learning.
- Practical Value: Enhances security in payment systems and supports real-time fraud detection.
# Step-by-Step Approach
- Problem Understanding & Objective Setting
- Define the problem: Fraud vs Non-Fraud classification.
- Business goal: Minimize false negatives (frauds that go undetected).
- Data Collection & Preprocessing
- Load dataset (payment_fraud.csv).
- Handle missing values.
- Convert categorical features into numeric form (e.g., one-hot encoding).
- Scale numerical features using StandardScaler.
# Exploratory Data Analysis (EDA)
- Distribution of fraud vs non-fraud transactions.
- Correlation heatmap to find relationships between features.
- Univariate & bivariate analysis (e.g., fraud by payment method, transaction amount).
- Check class imbalance.
# Feature Engineering
- Create derived features (e.g., transaction frequency per user, average transaction amount).
- Encode categorical variables (paymentMethod, deviceType, etc.).
- Apply scaling/normalization for numeric features.
# Feature Selection
- Use correlation analysis and feature importance (Logistic Regression coefficients, Random Forest importance).
- Drop irrelevant or redundant features.
# Model Training
- Train classification models:
- Logistic Regression (baseline)
- Decision Trees / Random Forest
- XGBoost / Gradient Boosting
- SVM / k-NN (optional)
# Model Testing & Validation
- Split dataset into train/test sets.
- Evaluate using metrics:
- Accuracy (overall correctness)
- Precision & Recall (important for fraud detection)
- F1-Score (balances precision and recall)
- Confusion Matrix (visual fraud detection performance)
# Model Training & Testing
- Baseline Model: Logistic Regression.
- Advanced Models: Random Forest & XGBoost.
- Evaluation:
- Confusion Matrix
- Precision-Recall Curve
- ROC-AUC Score
# Output
<img width="978" height="844" alt="Screenshot 2025-08-16 132810" src="https://github.com/user-attachments/assets/a81f245b-26a0-41ce-b3d5-f06b50aed8fa" />
