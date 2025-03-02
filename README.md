# Medical-Anomaly-Detection-using-ML-and-DL

This project aims to detect fraudulent or anomalous medical claims using various Machine Learning (ML) and Deep Learning (DL) models. The dataset consists of inpatient and outpatient claims, patient demographics, and reimbursement information. The goal is to classify claims as fraudulent or non-fraudulent using supervised learning techniques.

The dataset comprises four CSV files:

**Dataset**

Train_Beneficiarydata.csv – Patient demographics and health history

Train_Inpatientdata.csv – Inpatient claims data

Train_Outpatientdata.csv – Outpatient claims data

Train.csv – Main dataset linking all the above

**Data Processing** 

✔️ Merged inpatient and outpatient data

✔️ Aggregated claim amount, unique patients per provider, total claims

✔️ Handled missing values by replacing them with 0

✔️ Applied Label Encoding to the target variable (PotentialFraud)

✔️ Used SMOTE + Random Undersampling for class balancing

The following models were implemented and compared:

📌 Random Forest → Achieved 87% accuracy

📌 XGBoost → Best performing model with 97% accuracy

📌 Artificial Neural Network (ANN) → Achieved 92% accuracy

**Results**

✔️ XGBoost performed best with 97% accuracy, making it the most suitable model for deployment.

✔️ ANN reached 92% accuracy, showing that deep learning can be effective for complex data.

✔️ SMOTE alone caused overfitting, but combining SMOTE + Undersampling improved generalization.

✔️ Feature Engineering & Aggregation significantly improved accuracy.

