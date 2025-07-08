# Customer-Churn-Prediction
This project analyzes and predicts customer churn using a bank’s customer dataset. As a Data Analyst, I applied exploratory analysis, feature engineering, and machine learning techniques to identify patterns behind customer attrition and provide actionable insights for business teams.

 Objectives
Identify key features influencing customer churn.

Build a predictive model to classify customers at risk of leaving.

Provide data-driven insights to help reduce churn and improve customer retention.

📁 Dataset
Source: Kaggle – Bank Customer Churn Modeling

10,000+ rows | 14 columns

Target variable: Exited (1 = churned, 0 = retained)

🛠 Technologies Used
Python: Data cleaning, feature engineering, modeling

Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

SQL: Basic data querying and validation

Machine Learning: Random Forest Classifier

Visualization: Seaborn, Matplotlib, Tableau (external dashboard)

IDE: Spyder

✅ Key Steps
Data Cleaning & Preprocessing

Removed irrelevant features (CustomerId, Surname, RowNumber)

One-hot encoded Geography and Gender columns

Split into training (80%) and test (20%) sets

Exploratory Data Analysis (EDA)

Visualized distributions and churn ratios by age, balance, tenure, geography

Identified patterns via correlation heatmaps and bar plots

Model Training & Evaluation

Used RandomForestClassifier with 200 estimators

Achieved ~80% accuracy on test data

Evaluated using confusion matrix, precision, recall, and F1 score

Business Insights & Visualization

Created churn breakdown by geography, credit score, and tenure

Delivered recommendations for proactive customer engagement

📈 Results
Identified high-risk customer segments based on activity and tenure

Model achieved strong performance and interpretability

Business insights supported targeted retention campaigns
