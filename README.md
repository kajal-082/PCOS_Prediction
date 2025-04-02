# PCOS Prediction

## Project Overview
PCOS Prediction is a machine learning-based project aimed at predicting the existence of Polycystic Ovary Syndrome (PCOS) in women based on clinical and biochemical parameters. The objective is to improve early detection and assist healthcare professionals in diagnosis.

## Dataset
The dataset used for this project includes features such as:
- Age
- BMI (Body Mass Index)
- Insulin Levels
- Hormonal Imbalances
- Menstrual Cycle Irregularities
- Other relevant medical parameters

## Problem Statement
The objective is to develop a predictive model that can accurately estimate the likelihood of a woman having PCOS based on given input features. This can help in:
- Early detection and intervention.
- Reducing diagnostic delays.
- Providing additional decision-making support to healthcare professionals.

## Approach
1. **Data Preprocessing:**
   - Handling missing values.
   - Encoding categorical variables.
   - Feature scaling and transformation.

2. **Exploratory Data Analysis (EDA):**
   - Identifying patterns and correlations between different features.
   - Visualizing the impact of various health parameters on PCOS.

3. **Model Selection:**
   - Training various models such as Logistic Regression, Random Forest, SVM, and XGBoost.
   - Hyperparameter tuning for improved performance.

4. **Evaluation Metrics:**
   - Accuracy, Precision, Recall, F1-score, and AUC-ROC to assess model performance.

## Results
### Accuracy Scores of Different Models:
- **Logistic Regression:** [92.47]
- **Random Forest:** [96.58]
- **SVM:** [95.21]
- **Ensemble** [95.89]

The **Random Forest** achieved an **accuracy of [96.58%]** with an **F1-score of [0.97]**, demonstrating strong predictive capabilities for detecting PCOS.

## Future Improvements
- Integrating additional medical history data for better predictions.
- Enhancing feature selection with more clinically relevant variables.
- Deploying the model as a web-based tool for healthcare professionals.
