# Diseases-Prediction
Diabeties,Cancer,Pneumonia
Medical Condition Classification – End-to-End Solution
Project Overview
This repository presents a comprehensive approach to medical condition classification using real-world EHR data. The dataset consists of 10,000 patient records, with significant missing values (up to 62% in key features) and notable class imbalance (Diabetic: 60%, Pneumonia: 25%, Cancer: 15%). The goal was to develop a robust predictive model for accurate disease screening, even in the presence of these common healthcare data challenges.

Approach
Data Imputation: Leveraged medical domain knowledge to impute missing values for age, BMI, blood pressure, and glucose, achieving 100% data completeness.

Feature Engineering: Created 21 clinically relevant features and selected the top 15 based on predictive power.

Class Balancing: Utilized ADASYN to address class imbalance, increasing the representation of minority classes, particularly Cancer.

Modeling: Trained and optimized multiple ensemble models (XGBoost, Random Forest, Extra Trees) and constructed a voting ensemble for comparison.

Results
Best Model: XGBoost

Final Weighted F1-score: 0.88 (125% improvement over baseline)

Class-wise F1-scores:

Cancer: 0.84

Diabetic: 0.91

Pneumonia: 0.82

The final model demonstrates strong and balanced performance across all conditions, supporting reliable clinical screening even with imperfect EHR data.

Impact
This solution addresses real-world issues of missing data and class imbalance in healthcare datasets, enabling more dependable risk stratification and timely clinical intervention. The methodology can be adapted for similar challenges in other medical prediction tasks.
