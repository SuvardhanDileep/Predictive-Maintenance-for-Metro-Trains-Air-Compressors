Predictive Maintenance for Metro Train Air Compressors

Overview
This project uses machine learning to predict air leakage in the air compressor units of metro trains. By analyzing historical sensor data, the model helps enable proactive maintenance, reducing downtime and preventing major failures.

Dataset
Source: MetroPT-3 dataset
Records: 1.5 million+
Features: 15 sensor readings (pressure, temperature, motor current, etc.) and a target column (fault_status)

Problem Statement
Detect potential air leakage in metro train compressors before it happens, allowing maintenance teams to act in advance and minimize operational disruptions.

Approach
Data cleaning and preprocessing
Handling class imbalance with class weighting
Feature selection and importance analysis
Model training using Random Forest
Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix

Results
Recall (faults): 99%
F1-score (faults): 92%
The model accurately detects most fault cases, supporting proactive maintenance.
