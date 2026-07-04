A machine learning project that predicts individual medical insurance charges based on demographic and health features: age, sex, BMI, number of children, smoking status, and region.
Dataset: 1,338 records (insurance.csv) with 7 features.
Workflow:

Exploratory data analysis (distributions, correlation heatmap)
Feature engineering — created a bmi_category feature (Underweight/Normal/Overweight/Obese)
Preprocessing pipeline with ColumnTransformer: StandardScaler for numeric features, OneHotEncoder for categorical features
Model: Linear Regression via sklearn.pipeline.Pipeline
Evaluation: R², Adjusted R², MAE, MSE, RMSE, and 5-fold cross-validation
