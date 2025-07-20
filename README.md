# Liver Disease Prediction using ML

This project predicts liver disease using ML models on the Indian Liver Patient Dataset (ILPD). It uses preprocessing, feature selection, SMOTE, and compares various classifiers — with the best results from a stacking ensemble model.

---

## Dataset
- **Source**: UCI ILPD
- **Instances**: 583 (after cleaning: 580)
- **Features**: 11 → top features selected using ElasticNet
- **Target**: Liver disease (1) or Not (0)

---

## ML Pipeline
- Preprocessing: Missing value handling, outlier removal, encoding, scaling
- SMOTE for balancing classes
- Feature Selection: Elastic Net
- Models: LR, RF, SVC, KNN, LDA, AdaBoost, Bagging, Stacking

---

## Best Result (Stacking Classifier)
- **Accuracy**: 80%
- **Precision**: 90%
- **Recall**: 80%
- **F1-Score**: 85%
- **ROC-AUC**: 84.2%
