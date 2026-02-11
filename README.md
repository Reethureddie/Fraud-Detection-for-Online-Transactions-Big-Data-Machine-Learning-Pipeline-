# Fraud-Detection-for-Online-Transactions-Big-Data-Machine-Learning-Pipeline-
An end-to-end fraud detection system built using Hadoop (HDFS), Hive, and Python ML models to process large-scale transaction data and classify fraudulent activity.
Built a Big Data fraud detection pipeline using Hadoop (HDFS) and Hive for distributed data processing, and trained ML models (Random Forest, XGBoost, LightGBM) to classify fraudulent transactions, identifying XGBoost as the best-performing model.
**Project Overview**
This project demonstrates a real-world Big Data → Machine Learning workflow:

1. Stored large transaction datasets in HDFS
2. Structured and queried data using Hive
3. Exported processed data for ML modeling
4. Trained and evaluated multiple classification models

The goal was to compare ML algorithms and identify the best-performing model for fraud detection.
**🛠️ Technologies Used**

**Big Data:**
Hadoop (HDFS), Hive
**Machine Learning:**
Python, Scikit-learn, XGBoost, LightGBM
**🏗️ Architecture**
Local CSV Files
      ↓
HDFS (Hadoop Distributed Storage)
      ↓
Hive (Schema + SQL Queries)
      ↓
Structured Dataset Export
      ↓
Jupyter Notebook (ML Modeling)

**🗄️ Big Data Processing**

**Hadoop (HDFS)**
Uploaded large CSV files (~400MB)
Managed distributed storage
<img width="1053" height="161" alt="image" src="https://github.com/user-attachments/assets/7de58e57-4740-4725-b98a-51b95f0d28d3" />

**Hive**
1. Created structured tables
2. Loaded data into Hive
3. Executed SQL-style queries for preprocessing
<img width="1086" height="393" alt="image" src="https://github.com/user-attachments/assets/cb4b6d58-6fd9-4ab0-ab7e-7886b8a7c131" />

<img width="1077" height="611" alt="image" src="https://github.com/user-attachments/assets/9b47419d-a827-40de-a36f-b6a8f0540e81" />

<img width="1036" height="585" alt="image" src="https://github.com/user-attachments/assets/af0b3e83-482d-4e43-875c-67b2b741246e" />

<img width="1060" height="245" alt="image" src="https://github.com/user-attachments/assets/23d5870a-d1f7-4374-b964-c7b83dac415d" />

<img width="1059" height="146" alt="image" src="https://github.com/user-attachments/assets/24a8b275-f46d-4109-9a08-4e54519ed915" />

<img width="1056" height="368" alt="image" src="https://github.com/user-attachments/assets/4250d525-1647-480f-8da0-8f2866040df8" />

<img width="1099" height="224" alt="image" src="https://github.com/user-attachments/assets/89ba9b35-5863-4308-8fc1-60a727381cc8" />

<img width="1118" height="211" alt="image" src="https://github.com/user-attachments/assets/22653407-b1cc-42c5-a665-2ab1b7d7e3fd" />

<img width="1078" height="540" alt="image" src="https://github.com/user-attachments/assets/29e88e84-3457-4df9-b803-64cd1d94a16c" />

<img width="1099" height="221" alt="image" src="https://github.com/user-attachments/assets/7849a6e2-0405-4650-a08e-6cd55d696e89" />

<img width="1045" height="492" alt="image" src="https://github.com/user-attachments/assets/07103d51-5af2-46fe-a5da-b52479320259" />

**🤖 Machine Learning**

After Hive processing, the structured dataset was exported and modeled in Python.

**Models Compared:**
Random Forest
XGBoost
LightGBM
**Evaluation Metrics:**
Precision
Recall
F1-score
AUC
Confusion Matrix
**Result**
XGBoost achieved the best performance for fraud classification.







