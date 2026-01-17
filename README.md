# Heart Failure Prediction using Machine Learning

A comprehensive machine learning project that predicts the likelihood of heart failure in patients based on clinical and demographic features. This project compares Support Vector Machine (SVM) and Neural Network models to identify high-risk patients for early intervention.

## 🎯 Project Overview

Heart failure is a leading cause of death worldwide. This project leverages machine learning to analyze patient data and predict heart failure risk, enabling healthcare professionals to provide timely intervention and personalized treatment plans.

## 📊 Dataset Features

The dataset includes the following clinical and demographic features:

- **age**: Patient's age (years)
- **creatinine_phosphokinase**: CPK enzyme level in blood (mcg/L)
- **ejection_fraction**: Percentage of blood leaving the heart at each contraction (%)
- **platelets**: Platelet count in blood (kiloplatelets/mL)
- **serum_creatinine**: Serum creatinine level in blood (mg/dL)
- **serum_sodium**: Serum sodium level in blood (mEq/L)
- **time**: Follow-up period (days)
- **DEATH_EVENT**: Target variable (0 = No event, 1 = Heart failure event)

## 🛠️ Technologies Used

- **Python 3.x**
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning models and preprocessing
- **Keras/TensorFlow** - Neural network implementation

## 🚀 Models Implemented

### 1. Support Vector Machine (SVM)
- Classical machine learning approach
- Effective for binary classification
- Uses kernel tricks for non-linear decision boundaries

### 2. Neural Network (Deep Learning)
- Multi-layer architecture with ReLU activation
- Dropout layers for regularization
- Early stopping to prevent overfitting
- Adam optimizer with binary cross-entropy loss

## 📈 Methodology

1. **Data Exploration**: Analyze distributions, correlations, and patterns
2. **Data Preprocessing**: Standardization using StandardScaler
3. **Train-Test Split**: 80-20 split for model validation
4. **Model Training**: Train both SVM and Neural Network
5. **Evaluation**: Compare models using accuracy, precision, recall, F1-score
6. **Visualization**: Confusion matrices and performance metrics

## 🔍 Key Findings

- Feature correlation analysis reveals important predictors
- Model comparison provides insights into best approach
- Evaluation metrics demonstrate predictive capability
- Visualizations highlight model performance differences

## 📁 Project Structure
