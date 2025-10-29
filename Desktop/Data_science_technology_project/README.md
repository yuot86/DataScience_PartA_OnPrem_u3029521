University of Canberra
Unit: Data Science Technology and Systems (PG 11523)
Assignment: Part A – On-Premises Machine Learning Pipeline
Student Name: Yuot Deng Malual
Student ID: u3029521
Semester: S2 2025
Campus: Canberra

------------------------------------------------------------
PROJECT OVERVIEW
------------------------------------------------------------
This project demonstrates an end-to-end on-premises machine learning workflow for flight delay prediction. 
The task involves data preparation, feature engineering, model training, and evaluation using a local Python environment. 
Part A focuses on local implementation, while Part B extends the same workflow to the AWS SageMaker cloud platform.

------------------------------------------------------------
OBJECTIVES
------------------------------------------------------------
• Build an on-premises ML pipeline using Python and scikit-learn.
• Perform data extraction, cleaning, and feature engineering.
• Train a binary classification model to predict flight delays (>15 minutes).
• Evaluate model accuracy, precision, recall, and F1-score.
• Establish a baseline for cloud comparison (Part B).

------------------------------------------------------------
DATASET DETAILS
------------------------------------------------------------
Source: Bureau of Transportation Statistics (2014–2018)
Supplemented with: Weather data (temperature, humidity, wind speed, precipitation)
Data Volume: Approximately 1.65 million records (60 CSV files merged)
Target Variable: is_delay (1 = delayed, 0 = on-time)

------------------------------------------------------------
TOOLS AND LIBRARIES
------------------------------------------------------------
Environment: Jupyter Notebook / PyCharm Professional
Programming Language: Python 3
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Version Control: git, GitHub
Cloud Integration: AWS SageMaker (Part B)

------------------------------------------------------------
PIPELINE WORKFLOW
------------------------------------------------------------
1. Load and merge multiple CSV files.
2. Clean and preprocess data (remove nulls, encode categorical variables).
3. Feature engineering (airline, airport, weather conditions, date).
4. Split dataset (80% train, 15% validation, 15% test).
5. Train Logistic Regression model (baseline).
6. Evaluate accuracy and F1-score.
7. Compare model performance between local and cloud environments.

------------------------------------------------------------
RESULTS SUMMARY
------------------------------------------------------------
Model: Logistic Regression
Accuracy: 0.78–0.82
F1-Score: ~0.79
ROC-AUC: ~0.84
Comment: Achieved stable baseline for on-premises environment.

------------------------------------------------------------
REFERENCES
------------------------------------------------------------
• AWS SageMaker Developer Guide (2025 Edition)
• Bureau of Transportation Statistics Dataset (2014–2018)
• Data Science Technology and Systems PG (11523) – Assignment Guidelines (2025)
• AWS Academy Cloud Foundations Lab Tutorials

------------------------------------------------------------
NEXT PHASE
------------------------------------------------------------
Part B: Cloud-Based ML Implementation using AWS SageMaker.
Repository: DataScience_PartB_OnCloud_u3029521 (to be created)

------------------------------------------------------------
COPYRIGHT NOTICE
------------------------------------------------------------
© 2025 University of Canberra.
This work is submitted for academic purposes only.
