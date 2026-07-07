# Online Shoppers Purchase Prediction Using Machine Learning

## Project Overview

This project predicts whether an online shopper will make a purchase during a website visit. Using customer browsing behavior and session-related features, machine learning classification models are trained to identify purchase intention.

## Problem Statement

E-commerce businesses want to understand whether a visitor is likely to complete a purchase. This project builds a machine learning model to predict customer purchase intention, helping businesses improve marketing strategies and customer experience.

## Dataset Features

The dataset contains website session information such as:

### Visitor Activity

* Administrative
* Administrative_Duration
* Informational
* Informational_Duration
* ProductRelated
* ProductRelated_Duration

### Website Behavior

* BounceRates
* ExitRates
* PageValues
* SpecialDay

### Visitor Information

* OperatingSystems
* Browser
* Region
* TrafficType
* VisitorType
* Weekend
* Month

### Target Variable

* Revenue

  * **True** → Customer made a purchase
  * **False** → Customer did not make a purchase

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Multicollinearity Analysis (VIF)
6. Feature Engineering
7. Data Preprocessing
8. Model Training
9. Model Evaluation
10. Model Comparison

## Machine Learning Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier
* Support Vector Machine (SVM)

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

## Data Preprocessing

* Missing Value Handling
* Duplicate Removal
* Label Encoding
* One-Hot Encoding
* Feature Scaling
* ColumnTransformer
* Pipeline Implementation

## Key Insights

* Visitor browsing behavior strongly influences purchase intention.
* Features such as **PageValues**, **ExitRates**, and **ProductRelated** activity play an important role in prediction.
* Comparing multiple classification models helps identify the best-performing model.

## Project Structure

```text
Online-Shoppers-Purchase-Prediction/
│
├── online_shoppers_purchase_prediction.ipynb
├── online_shoppers_intention.csv
├── README.md
```

## Future Improvements

* Hyperparameter tuning using Optuna or GridSearchCV.
* Deploy the model using Streamlit.
* Build a real-time purchase prediction application.

## Author

**Chandramouli Neerukonda**

* GitHub: https://github.com/Chandramouli299
* LinkedIn: https://www.linkedin.com/in/chandramouli-neerukonda-69204a268/
