# IPD_Manumi_20221050
Fraud Detection with financial transactions
Project Overview

This project develops a high-performance machine learning model to detect fraudulent financial transactions. Using the synthetic dataset (6.3 million records), the system addresses extreme class imbalance and identifies key behaviorals of fraud.

Technical Architecture
Language: Python 3.x

Environment: Google Colab (High-RAM Runtime)

Key Libraries: Pandas, XGBoost, Scikit-Learn, Imbalanced-Learn (SMOTE), Seaborn

CSV File- Due to file size limitations, the Fraud.csv dataset is not hosted in this repository. 
It can be downloaded from Kaggle: https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data

Key Features of the Prototype
Optimized Loading: Uses chunksize processing to handle 6M+ rows without memory crashes but for further data sampling around 500,000 records are taken.

Feature Engineering: Includes custom logic like errorBalance (detecting discrepancies in transaction math) and hour (temporal analysis).

Class Balancing: Implements SMOTE (Synthetic Minority Over-sampling Technique) to ensure the model can accurately identify rare fraud cases.


