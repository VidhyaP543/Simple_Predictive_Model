#  Model Findings Report - Task 4
## 1. Project Overview
This project focuses on building a simple machine learning classification model using the Breast Cancer dataset from Scikit-learn. The goal is to predict whether a tumor is malignant or benign based on medical features.
---
## 2. Problem Type
This is a **binary classification problem**, where the output has two classes:
- 0 → Malignant
- 1 → Benign
---
## 3. Model Used
A **Logistic Regression** model was used as a baseline classifier because:
- It is simple and efficient for binary classification
- It provides good interpretability
- It performs well on linearly separable data
---
## 4. Data Preparation
- Dataset loaded using Scikit-learn
- Features (X) and target (y) separated
- Data split into training (80%) and testing (20%) sets using train_test_split
- Random state used for reproducibility
---
## 5. Model Evaluation Metrics
The model was evaluated using the following metrics:
- **Accuracy Score**: Measures overall correctness of predictions
- **F1 Score**: Balances precision and recall
- **Confusion Matrix**: Shows correct and incorrect predictions
---
## 6. Confusion Matrix Insights
The confusion matrix shows:
- True Positives: Correct positive predictions
- True Negatives: Correct negative predictions
- False Positives: Incorrect positive predictions
- False Negatives: Incorrect negative predictions
The model shows good performance with minimal misclassification.
---
## 7. Results Summary
- The Logistic Regression model performed well as a baseline model
- Accuracy was high, indicating good prediction capability
- Confusion matrix shows most predictions were correct
---
## 8. Conclusion
This project successfully demonstrates a basic machine learning pipeline including data preprocessing, model training, prediction, and evaluation.
---
## 9. Future Improvements
- Try advanced models like Random Forest or SVM
- Perform feature scaling for better performance
- Apply hyperparameter tuning for optimization
