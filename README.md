# Portfolio Overview

# Default Credit Card Clients Prediction

## Overview
This project focuses on predicting credit card defaults using various classification models. The objective is to classify whether a client will default on their credit card payment based on a set of features. The project involves several key steps, including data import, preprocessing, model building, and optimization.

## Key Steps
- **Data Import**: Data is imported and cleaned to prepare it for modeling.
- **Preprocessing**: Includes handling missing values, encoding categorical variables, and scaling numerical features.
- **Model Building**: Several classification models are trained, including decision trees, random forests, SVM, and CatBoost.
- **Model Evaluation**: Models are evaluated using metrics like accuracy, precision, recall, and ROC-AUC curve.
- **Optimization**: The CatBoost model is fine-tuned for improved performance.
- **Feature Importance**: Univariate analysis is used to identify and prioritize important features.

## Results
The project demonstrates the effectiveness of combining multiple preprocessing and modeling techniques to improve classification accuracy. The CatBoost model, after tuning, emerged as the best-performing model.

## Visualizations
- ROC & AUC Curve
- Precision-Recall Trade-off Curve

### ROC & AUC Curve
![ROC Curve](images/roc_curve.png)
Include your ROC curve image here.

### Precision-Recall Trade-off Curve
![Precision-Recall Curve](images/pr_curve.png)
Include your Precision-Recall curve image here.

## Conclusion
In conclusion, the project successfully predicts credit card defaults with high accuracy using advanced classification techniques. Future work could explore ensemble methods or more robust feature engineering to further enhance model performance.


