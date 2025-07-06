# Stroke Prediction using Multiple Machine Learning Models

This project focuses on predicting the likelihood of a patient suffering from a stroke using various machine learning classifiers. The process includes data preprocessing, handling class imbalance, and comparing multiple models.

## 📊 Dataset

- **Source**: [Kaggle - Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- **Features**: Demographic and health-related information (age, gender, hypertension, heart disease, work type, smoking status, etc.)
- **Target**: `stroke` (0 = No Stroke, 1 = Stroke)

## 🧠 Models Used

- Logistic Regression  
- Naive Bayes  
- K-Nearest Neighbors  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)

## 🔧 Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Seaborn & Matplotlib

## ⚙️ Workflow

1. Load and inspect the dataset
2. Handle missing values
3. Encode categorical variables
4. Normalize features
5. Apply SMOTE for class balancing
6. Train and evaluate multiple classifiers
7. Compare results using Accuracy, Precision, Recall, and F1-Score

## 📈 Evaluation Metrics

Here is the classification report of the best performing model:

          precision    recall  f1-score   support

       0       0.95      0.91      0.93       975
       1       0.91      0.95      0.93       970

accuracy                           0.93      1945


