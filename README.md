# Machine-Learning-Based-Predictive-Analysis-of-Heart-Failures

# Project Overview
This project focuses on predicting heart failure using machine learning techniques. By leveraging patient health metrics, the analysis identifies patterns and predicts the likelihood of heart failure.

# Dataset
The dataset used is sourced from Kaggle, containing key health-related features that contribute to heart health analysis:

- **Age:** The age of the patient.
- **Ejection Fraction:** Measurement of the percentage of blood leaving the heart each time it contracts.
- **Serum Creatinine:** Blood levels of creatinine, indicating kidney function.
- **Time:** Follow-up period in days.
- **Other Features:** Additional health metrics such as blood pressure and diabetes indicators.

# Data Pre-processing
- Missing values are checked and handled appropriately.
- Redundant columns are removed for better performance and clarity.
- Feature scaling is applied using MinMaxScaler to normalize data values.
- Correlation analysis identifies relationships between variables to reduce multicollinearity.
- Target variable encoding: Binary encoding is used for classification.

# Data Visualization
- Countplot to show the distribution of Death Events.
- Histogram plots show the distribution of key features such as age and ejection fraction.
- A correlation heatmap highlights significant relationships among variables.

# Model building and Training
- Support Vector Machine **(SVM)**
- Logistic Regression **(LR)**
- Artificial Neural Networks **(ANN)**
- Data is divided into **80%** training and **20%** testing.

# Model Evaluation
Performance is assessed using:
- **Confusion Matrix**: Evaluates true positives, false positives, false negatives, and true negatives.
- **Classification Report**: Provides precision, recall, F1-score, and accuracy for each model.
- **ROC-AUC Curve**: Used to measure the trade-off between true positive rate and false positive rate.

# Results
- **SVM:** Accuracy: 80%, ROC-AUC: 0.77
- **Logistic Regression:** Accuracy: 80%, ROC-AUC: 0.77
- **ANN:** Accuracy: 73%, ROC-AUC: 0.70

# Libraries Used
- pandas
- numpy
- sklearn
- seaborn
- matplotlib
