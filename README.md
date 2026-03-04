# Diabetes_Prediction-ML-

A simple machine learning project that predicts whether a person is diabetic using the Pima Indians Diabetes dataset. The pipeline loads the dataset, standardizes features, trains a linear SVM classifier, evaluates accuracy on train/test splits, and supports single-user predictions from manual input.

## Model + Pipeline
- Dataset: `diabetes.csv` (contains medical features + `Outcome`)
- Preprocessing: `StandardScaler` (fit on training features)
- Train/Test Split: 80/20 with stratification (`random_state=2`)
- Model: Support Vector Machine (SVM) with a linear kernel
- Metric: Accuracy score (train + test)

