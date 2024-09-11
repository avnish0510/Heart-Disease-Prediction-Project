## Heart Disease Prediction Project

### Overview

This project involves predicting the likelihood of heart disease in patients based on various medical attributes. Utilizing a dataset containing comprehensive patient information, we employ data analysis and machine learning techniques to develop a model capable of predicting heart disease presence.

### Dataset

The dataset used for this project is a CSV file with the following columns:

- **age**: Age of the patient
- **sex**: Gender of the patient (1 = male, 0 = female)
- **cp**: Chest pain type (0-3)
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum cholesterol level (in mg/dl)
- **fbs**: Fasting blood sugar (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (0-2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes, 0 = no)
- **oldpeak**: Depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (0-2)
- **ca**: Number of major vessels colored by fluoroscopy (0-3)
- **thal**: Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect)
- **target**: Presence or absence of heart disease (1 = presence, 0 = absence)

### Objectives

1. **Data Cleaning**: The initial phase involves handling missing values, outliers, and ensuring the data is in a format suitable for analysis.
2. **Exploratory Data Analysis (EDA)**: Through visualization and statistical analysis, we explore patterns and correlations within the dataset to understand the features affecting heart disease.
3. **Feature Engineering**: Refining features and preparing the dataset for modeling.
4. **Model Building**: Implementing and training a Logistic Regression model to predict the likelihood of heart disease based on the features.
5. **Evaluation**: Assessing the model's performance using metrics such as accuracy, precision, recall, and F1 score.

### Tools and Libraries

- **Pandas**: For data manipulation and cleaning.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.
- **Scikit-learn**: For implementing the Logistic Regression model and evaluating its performance.

### Results

The project demonstrates the application of logistic regression in predicting heart disease and provides insights into which features are most influential. 
Visualizations and model performance metrics are detailed in the provided Jupyter Notebook.
