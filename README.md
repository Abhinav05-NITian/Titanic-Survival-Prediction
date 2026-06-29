# Titanic Survival Prediction

## Project Overview
This project predicts whether a passenger survived the Titanic disaster using Machine Learning models.

## Dataset
- Titanic Dataset
- 891 samples
- Binary Classification Problem

## Data Preprocessing
- Missing value handling
- Median imputation for Age
- Mode imputation for Embarked
- One-hot encoding for categorical variables
- Feature scaling using StandardScaler

## Models Used
1. Logistic Regression
2. Decision Tree
3. Random Forest

## Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 81.34% |
| Decision Tree | 76% |
| Random Forest | 77% |

## Cross Validation
5-Fold Cross Validation Accuracy:

78.56%

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

## Future Improvements
- Feature Engineering
- Hyperparameter Tuning
- XGBoost
- Deployment using Streamlit
