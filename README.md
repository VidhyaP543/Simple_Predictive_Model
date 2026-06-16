# Simple_Predictive_Model
#  Simple Predictive Machine Learning Model
##  Overview
This project demonstrates a simple machine learning classification model using Python and Scikit-learn. The goal is to predict whether a tumor is malignant or benign using the Breast Cancer dataset.
---
##  Objective
- Build a basic ML classification model
- Understand full ML workflow
- Evaluate model using standard metrics
---
##  Dataset
- Source: Scikit-learn Breast Cancer dataset
- Type: Binary Classification
- Classes:
  - 0 → Malignant
  - 1 → Benign
---
##  Model Used
- Logistic Regression (Baseline Model)
---
##  Workflow
1. Load dataset
2. Split into features and target
3. Train-test split (80/20)
4. Train Logistic Regression model
5. Predict test results
6. Evaluate model performance
---
##  Evaluation Metrics
- Accuracy Score
- F1 Score
- Confusion Matrix
---
##  Results
- Model performed well on test data
- Confusion matrix shows most predictions are correct
- Minimal errors observed
---
##  Project Structure
ML_Task_4/
├── README.md
├── requirements.txt
├── notebooks/model_training.ipynb
├── docs/findings.md
├── images/evaluation_plots.png
---
##  How to Run
pip install -r requirements.txt  
jupyter notebook  
---
##  Future Improvements
- Try Random Forest / SVM
- Feature scaling
- Hyperparameter tuning
