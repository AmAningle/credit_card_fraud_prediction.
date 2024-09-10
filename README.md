
---

# Credit Card Fraud Detection with PCA and Machine Learning

This project implements credit card fraud detection using machine learning algorithms and Principal Component Analysis (PCA) for dimensionality reduction. The dataset is highly imbalanced, and various algorithms are applied to classify fraudulent transactions.

 **Model Used**
   - Implemented and evaluated the following machine learning models:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Decision Tree
     - Random Forest
     - XGBoost Classifier

**Handling Class Imbalance**
   - Addressed class imbalance using class weighting.

     
**Results**

   Here’s the revised table showing only the ROC AUC scores for each model:

---

## Model Performance - ROC AUC

| Model                    | ROC AUC |
|--------------------------|---------|
| Logistic Regression      | 79.18%  |
| K-Nearest Neighbors (KNN) | 51.47%  |
| Decision Tree            | 80.84%  |
| Random Forest            | 81.25%  |
| XGBoost Classifier       | 88.95%  |

---



   - **XGBoost Classifier** achieved the highest ROC-AUC (88.95%).



