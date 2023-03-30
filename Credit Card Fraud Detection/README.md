# **Fraud Detection Mastery**

## **Project Overview**

Credit card fraud is a prevalent problem that costs billions of dollars each year. The goal of this project is to explore various machine learning algorithms and techniques to predict credit card fraud. The target variable is highly unbalanced, making it a challenging problem. To handle this issue, we applied Undersampling, Subsampling, and Synthetic Data Generation techniques.

Additionally, we evaluated the performance of various algorithms, including Decision Tree, Logistic Regression, KNN, GaussianNB, BernoulliNB, Random Forest, XGB, Gradient Boosting, LGBM, Support Vector Machine, and Multilayer Perceptron. We compared the performance of these algorithms using precision, recall, f1, and roc_auc_score metrics.

Our project workflow involved data exploration, preprocessing, and modeling, along with techniques for handling the unbalanced target variable. We also conducted hyperparameter tuning for the best-performing algorithms. The final stage involved drawing conclusions based on the results obtained and discussing the effectiveness of the various techniques and algorithms used in this project.

## **Workflow**

Our project workflow consisted of the following stages:

1. **Data Exploration:** In this stage, we performed univariate and bivariate analytics to gain a better understanding of the data.
2. **Preprocessing:** This stage involved data cleaning, feature selection, and transformation to prepare the data for modeling.
3. **Modeling:** We applied various machine learning algorithms to build models and handle the unbalanced target variable. We also used techniques such as Undersampling, Subsampling, and Synthetic Data Generation.
4. **Comparing Performance Metrics:** We compared the performance of different algorithms using metrics such as precision, recall, f1, and roc_auc_score. This stage involved testing various algorithms and conducting hyperparameter tuning to optimize their performance.
5. **Optimized Algorithm Performance:** After hyperparameter tuning, we evaluated the performance of the optimized algorithms.
6. **Conclusion:** In the final stage, we drew conclusions based on the results obtained and discussed the effectiveness of the various techniques and algorithms used in this project.

## **Repository Navigation**

- **`data`**: contains the raw and processed data used in the project.
- **`notebooks`**: contains the Jupyter notebooks used to perform the data exploration, preprocessing, modeling, and evaluation stages.
- **`results`**: contains the evaluation metrics and visualizations generated during the project.
- **`README.md`**: provides an overview of the project.

## **Dependencies**

The project was developed using Python 3.9.7 and the following packages:

- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- imblearn
- lightgbm
- xgboost

You can install these packages using **`pip`**:

```
bashCopy code
pip install -r requirements.txt

```
