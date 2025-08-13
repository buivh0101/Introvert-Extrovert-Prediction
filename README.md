# Introvert-Extrovert Prediction

Classify a person as introvert or extrovert with machine learning.

## Dataset
- Train: 18,524 rows × 9 columns (7 features, target, ID)
- Test: 6,175 rows × 8 columns (7 features, ID)
- Target: Personality (Introvert / Extrovert)
- Mix of numeric and categorical features

## Methods
- EDA and plots
- Preprocessing
  - OneHotEncoder for categorical
  - StandardScaler for numeric
  - ColumnTransformer + Pipeline
- Models
  - RandomForestClassifier
  - XGBClassifier
  - CatBoostClassifier
- Tuning
  - Optuna for RF, XGB, CatBoost
- Evaluation
  - Accuracy, Precision, Recall, F1
  - Confusion matrix, classification report
- Ensemble
  - Majority vote of RF + XGB + CatBoost
  - Soft voting by averaging predicted probabilities
