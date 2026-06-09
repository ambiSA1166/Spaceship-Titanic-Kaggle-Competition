# Spaceship Titanic - Machine Learning Solution

My Kaggle solution for the Spaceship Titanic competition. A project focused on ML pipelines, using `KNNImputer` for missing data and custom feature engineering to boost model performance. The pipeline benchmarks five different classification models: Logistic Regression, Decision Tree Classifier, Random Forest Classifier, XGBClassifier, and LGBMClassifier, achieving a 0.80430 public leaderboard score[cite: 1].

## Key Features
* **Data Imputation:** Handled missing values using `KNNImputer`.
* **Feature Engineering:** Created aggregate billing features (`amt_spent`, `std_amt_spent`, `mean_amt_spent`) to improve predictive power.
* **Model Benchmarking:** Compared performance across: Logistic Regression, Decision Tree Classifier, Random Forest Classifier, XGBClassifier, and LGBMClassifier.
