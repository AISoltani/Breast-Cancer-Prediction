# Breast-Cancer-Prediction

## Breast Cancer Prediction - Machine Learning Project

Summary
This project focuses on predicting the presence of breast cancer based on a given dataset. The goal is to build a machine learning model that accurately classifies whether a tumor is malignant or benign using a set of relevant features. The process involves data preprocessing, feature engineering, model training, and evaluation.


Steps Involved
1. Column Removal
To ensure that only the most relevant features are used for the prediction, unnecessary columns were removed from the dataset. This step helps to simplify the model, improve performance, and avoid overfitting.

2. Data Visualization
Various data visualizations were performed to explore the dataset and understand the relationships between different features. Key insights gained from visualizing the data include:

Distribution of numerical features
Correlations between features
Identification of potential outliers or anomalies
3. Standardization and Label Encoding
Standardization: Numerical features were standardized to ensure that they are on the same scale. This step improves the performance and stability of the machine learning model, especially for algorithms like Logistic Regression.
Label Encoding: Categorical variables were label-encoded to convert non-numeric categories into numeric format, making them suitable for machine learning algorithms.
4. Model Training
A Logistic Regression model was used for this classification task. Logistic Regression is chosen because it is simple, interpretable, and works well for binary classification problems like predicting whether a tumor is malignant or benign.

5. Model Performance
The trained Logistic Regression model achieved an accuracy of 97.4%, which indicates excellent performance in predicting the presence of breast cancer. This high accuracy suggests that the model is well-suited for the task and is able to make reliable predictions based on the input features.
***
  <img src="https://raw.githubusercontent.com/AISoltani/Breast-Cancer-Prediction/refs/heads/main/BreastCancerPR.png" alt="Breast Cancer Prediction Model" width="600"/>

# Conclusion
The project successfully demonstrates the process of predicting breast cancer using a machine learning model. With a high accuracy rate of 97.4%, the Logistic Regression model shows promising results in classifying tumors as malignant or benign. Further improvements can be made by experimenting with other machine learning algorithms, fine-tuning hyperparameters, and performing cross-validation to ensure robustness.

Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
