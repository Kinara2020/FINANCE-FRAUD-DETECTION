Financial Fraud Detection

A machine learning system that detects fraudulent financial transactions in real time. Built to address the growing challenge of payment fraud by identifying suspicious patterns in transaction data.

Features

	•	Binary classification of transactions as fraudulent or legitimate
	•	Handles highly imbalanced datasets using SMOTE / class weighting
	•	Feature engineering on transaction amount, frequency, location, and time patterns
	•	Model evaluation with precision, recall, F1-score, and AUC-ROC
	•	Threshold tuning to minimize false negatives in high-risk scenarios

Tech Stack

Python, scikit-learn, pandas, numpy, matplotlib, imbalanced-learn
Model options: Random Forest, XGBoost, Logistic Regression

Setup

	1.	Clone the repository
	2.	Install dependencies: pip install -r requirements.txt
	3.	Place your dataset in the /data directory
	4.	Run preprocessing: python preprocess.py
	5.	Train the model: python train.py
	6.	Evaluate: python evaluate.py

Dataset

Designed to work with standard fraud detection datasets such as the PaySim synthetic dataset or the Kaggle Credit Card Fraud Detection dataset. Update the data path in config.py before running.


Project Status

Core pipeline complete. Potential extensions include real-time API deployment, explainability with SHAP values, and integration with a transaction monitoring dashboard.
