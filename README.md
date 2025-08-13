# Introvert-Extrovert Prediction

Machine learning model to classify introvert vs extrovert using multiple algorithms and feature engineering.

## Dataset
- **Train:** 18,524 rows, 9 columns (7 predictors, target, ID)
- **Test:** 6,175 rows, 8 columns (7 predictors, ID)
- **Features:** mix of numerical and categorical
- **Target:** Personality (Introvert / Extrovert)

## Steps
- Data loading and exploration
- Handle missing values
- Encode categorical features
- Scale numerical features
- Train/test split
- Model training:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - LightGBM
  - CatBoost
  - SVM
  - KNN
  - Gradient Boosting
- Evaluate models (accuracy, precision, recall, F1 score)
- Ensemble models for better performance

## Results
- **Best model:** Ensemble of top classifiers
- **Metrics:** Accuracy and F1 score highest among tested models
