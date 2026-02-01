# airlaner-passenaer-statisfaction
📌 Project Overview

This project focuses on predicting airline passenger satisfaction using machine learning techniques.
The main emphasis of the project is data analysis, feature engineering, model development, and explainability, rather than deployment.

The goal is to demonstrate a solid data science workflow that reflects how real-world machine learning projects are designed and evaluated in practice.

⸻

🎯 Business Problem

Airlines collect detailed passenger feedback related to:
	•	service quality,
	•	digital experience,
	•	comfort,
	•	flight delays,
	•	and overall travel satisfaction.

Objective:
Build a classification model that predicts whether a passenger is satisfied and identify the key drivers behind passenger satisfaction.

⸻

📊 Dataset
	•	Source: Airline Passenger Satisfaction Dataset
	•	Target Variable: satisfaction (binary)
	•	Feature Groups:
	•	Service ratings (WiFi, Online Boarding, Seat Comfort, etc.)
	•	Flight-related information (distance, delays)
	•	Passenger type and travel class

⸻

🧠 Project Scope & Workflow

1️⃣ Exploratory Data Analysis (EDA)
	•	Categorical & numerical variable analysis
	•	Missing value detection
	•	Target distribution analysis
	•	Statistical summaries

2️⃣ Feature Engineering
	•	Composite service quality scores
	•	Delay-based indicators
	•	Binary flags and ratio features
	•	Outlier handling for numerical variables

3️⃣ Base Models
	•	Baseline model evaluation
	•	Performance comparison using ROC-AUC and F1-score

4️⃣ XGBoost Model & Hyperparameter Tuning
	•	Model: XGBoost Classifier
	•	Hyperparameter optimization using:
	•	GridSearchCV
	•	StratifiedKFold
	•	Optimization metric: ROC-AUC

5️⃣ Overfitting Control
	•	Comparison of training vs test performance
	•	Cross-validation metrics on training data

6️⃣ Model Explainability (SHAP)
	•	Global feature importance analysis
	•	SHAP summary and bar plots
	•	Dependence plots for key features
	•	Local explanations using waterfall plots

7️⃣ Pipeline Creation
	•	End-to-end machine learning pipeline including:
	•	Missing value imputation
	•	Feature scaling
	•	Trained XGBoost model

8️⃣ Model Persistence
	•	Final pipeline saved using joblib
	•	Model is reusable and ready for integration into an application environment

⸻

📈 Model Performance (Final)
	•	ROC-AUC: ~0.99
	•	Accuracy: ~94%
	•	F1-score: ~0.94

The model demonstrates strong generalization with controlled overfitting.
