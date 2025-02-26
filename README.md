# **Predictive Modeling for Diabetes Diagnosis**

## **Overview**
This project aims to predict the presence of diabetes using the Pima Indians Diabetes dataset, which contains health-related attributes such as glucose levels, BMI, insulin levels, and age. Two machine learning models are implemented and compared:

- **Logistic Regression** - A simple yet interpretable model that predicts the probability of diabetes.
- **Random Forest Classifier** - An ensemble learning method that enhances prediction accuracy by combining multiple decision trees.

The models are evaluated based on **accuracy, precision, recall, F1-score**, and **ROC curve analysis**.

## **Technologies Used**
- **Programming Language**: Python  
- **Libraries**:  
  - **Scikit-learn** - Model training, evaluation, and performance metrics  
  - **Pandas & NumPy** - Data handling and preprocessing  
  - **Matplotlib & Seaborn** - Data visualization  

## **Model Performance**
| **Model** | **Accuracy** | **Precision** | **Recall** | **F1-Score** |
|-----------|-------------|--------------|------------|--------------|
| **Logistic Regression** | ~77% | **0.75** | **0.74** | **0.74** |
| **Random Forest** | ~81% | **0.79** | **0.78** | **0.78** |

## **Key Features**
✔ **Data Preprocessing**: Handled missing values, standardized features, and split the dataset into training and test sets.  
✔ **Model Training & Evaluation**: Implemented **Logistic Regression** and **Random Forest** models.  
✔ **ROC Curve Analysis**: Visualized model performance using **Receiver Operating Characteristic (ROC) curves**.  
✔ **Feature Importance**: Identified key health attributes influencing diabetes prediction.  

- **Random Forest outperformed Logistic Regression**, demonstrating the benefits of ensemble learning in handling complex data relationships.
- The project provides insights into the **importance of health attributes** in predicting diabetes risk and supports the use of machine learning for **early disease detection**.
