### Description

There are two goals with this project;

1) To develop a robust machine learning model that accurately predicts bank customer churn based on the features provided.

2) To conduct exploratory data analysis (EDA) that allows stakeholders to explore and understand customer data, identifying key patterns and insights related to churn behavior.

### Dataset

The full dataset is linked here [Link](https://www.kaggle.com/datasets/divu2001/customer-churn-rate?select=Churn_Modelling.csv)

10,000 entries, total 14 columns - Memory Usage: 1.1+ MB

### Notebook

Models used 

- Logistic Regression
- Nearest Neighbors
- Support Vectors
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- Naive Bayes
- Quadratic DA
- Neural Net

Final model

- Random Forest - {'bootstrap': True, 'max_depth': 7, 'min_samples_leaf': 1, 'min_samples_split': 2, 'n_estimators': 50}

### Tech-stack + Libraries

- **Python version**: 3.10.12
- **Packages**: pandas, numpy, seaborn, matplotlib, sklearn
- **Visualisation Tool**: Tableau

### **Results**

| Metric | Value |
| --- | --- |
| Best Score Achieved | 0.858 |
| Accuracy on Training Set | 0.868 |
| Accuracy on Validation Set | 0.867 |

| 184 | 221 |
| --- | --- |
| 46 | 1549 |

<img width="471" alt="Screenshot 2024-08-13 at 22 47 03" src="https://github.com/user-attachments/assets/b80bb237-4d05-4d2e-8d47-764388a8d9f1">

### EDA

12 python - seaborn visualisations

[(*Embed Tableau Dashboard*)](https://github.com/dinkwiz/tableau_embed?tab=readme-ov-file)
