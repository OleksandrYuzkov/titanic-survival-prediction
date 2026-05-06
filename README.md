# Titanic Survival Prediction

Predicting passenger survival using exploratory data analysis, feature engineering and machine learning.

## Results
| Model | Accuracy | F1 | ROC-AUC |
|---|---|---|---|
| XGBoost | 84.5% | 0.788 | 0.890 |
| RandomForest | 83.6% | 0.769 | 0.884 |
| LogisticRegression | 81.5% | 0.754 | 0.864 |

## Structure
1. **Imports & Setup** — libraries and style configuration
2. **Load Data** — loading and first look at the dataset
3. **EDA** — distribution analysis, survival rates, correlations
4. **Feature Engineering** — Title, FamilySize, FareBin, AgeBin, HasCabin, SexPclass
5. **Modeling** — 5-fold cross-validation, model comparison, hyperparameter tuning

## Tech Stack
`Python` `pandas` `numpy` `matplotlib` `seaborn` `scikit-learn` `XGBoost`

## Data
Dataset from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic).
Download `train.csv` and place them in the root folder.
