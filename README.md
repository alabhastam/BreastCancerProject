# Breast Cancer Classification with Tree-Based Models

This project applies several state-of-the-art tree-based machine learning models to classify breast cancer using a real-world dataset.

## Models Trained

- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**
- **XGBoost**
- **LightGBM**

## Workflow

1. **Data Preparation**
    - Data cleaned and preprocessed (label encoding, feature selection)
    - Train/test split with stratification

2. **Model Training**
    - All models trained on the same training data
    - Consistent random state for reproducibility

3. **Model Evaluation**
    - Metrics: Accuracy, Precision, Recall, F1-Score
    - Classification reports and confusion matrices for each model
    - Results presented in a comparison table

4. **Feature Importance**
    - Visualized top features for Random Forest (and available in other models)
    - Code designed for extensibility to other tree-based models

## Results

=== Model Comparison Table ===
            Model  Accuracy  Precision   Recall  F1-score
    random_forest  0.973684   1.000000 0.928571  0.962963
gradient_boosting  0.964912   1.000000 0.904762  0.950000
         lightgbm  0.964912   1.000000 0.904762  0.950000
          xgboost  0.956140   1.000000 0.880952  0.936709
    decision_tree  0.929825   0.904762 0.904762  0.904762

(**Replace the “...” with your actual numbers!**)

- Random Forest and gradient boosting models demonstrated the highest performance on most metrics.
- Feature importance visualization highlighted the top diagnostic predictors.

## Next Steps (Optional/Future Work)

- ROC and precision-recall curve plotting for all models
- Hyperparameter optimization (GridSearchCV/RandomizedSearchCV)
- Advanced explainability methods (e.g., SHAP, LIME)
- Model deployment (pickle/joblib for API or app use)
- Error analysis and reporting

---

[*This summary and some code comments in this notebook were generated with the help of [OpenAI’s ChatGPT-4.1](https://openai.com) for clarity, reporting, and best practices.*

---
