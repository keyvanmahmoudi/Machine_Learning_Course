# Machine Learning Course

Practical notebooks covering the core machine learning toolkit with scikit-learn, Keras and XGBoost: data preprocessing, regression, classification, clustering, dimensionality reduction, neural networks and model selection. Every notebook runs end to end on a small dataset from the [`dataset/`](dataset) folder.

## Contents

| # | Notebook | Topics | Datasets |
|---|---|---|---|
| 1 | [Data Preprocessing](1.%20Data_Preprocessing.ipynb) | Handling missing values, train/test split, feature scaling | `Data.csv` |
| 2 | [Regression](2.%20Regression.ipynb) | Simple and multiple linear regression, backward elimination, polynomial regression, SVR, decision tree and random forest regression | `Salary_Data.csv`, `50_Startups.csv`, `Position_Salaries.csv` |
| 3 | [Classification](3.%20Classification.ipynb) | Logistic regression, k-NN, SVM, kernel SVM, Naive Bayes, decision tree and random forest classification | `Social_Network_Ads.csv`, `PastHires.csv` |
| 4 | [Clustering](4.%20Clustering.ipynb) | K-means (elbow method) and hierarchical clustering (dendrograms) | `Mall_Customers.csv` |
| 5 | [Dimensionality Reduction](5.%20Dimensionality_Reduction.ipynb) | PCA, LDA and kernel PCA | `Wine.csv`, `Social_Network_Ads.csv` |
| 6 | [Artificial Neural Networks](6.%20Artificial_Neural_Networks_(ANN).ipynb) | A feed-forward network for customer churn prediction with Keras | `Churn_Modelling.csv` |
| 7 | [Model Selection & Boosting](7.%20Model_Selection_&_Boosting.ipynb) | k-fold cross-validation, grid search, XGBoost | `Social_Network_Ads.csv`, `Churn_Modelling.csv` |

The `dataset/` folder also contains `Market_Basket_Optimisation.csv` (association rules) and `Restaurant_Reviews.tsv` (text classification) for exercises.

## Getting started

Open a notebook in Google Colab and upload the dataset it uses, or run locally:

```bash
git clone https://github.com/keyvanmahmoudi/Machine_Learning_Course.git
cd Machine_Learning_Course
pip install jupyter numpy pandas matplotlib scikit-learn statsmodels scipy keras tensorflow xgboost pydotplus
jupyter notebook
```

Notebooks read their CSV files by file name, so either run them from the folder that contains the data or adjust the path in the loading cell (for example `dataset/Data.csv`).

## Prerequisites

Basic Python, NumPy and pandas. The companion course [Python and Data Analysis](https://github.com/keyvanmahmoudi/Python-and-data-analysis) covers these from scratch.

## Author

**Keyvan Mahmoudi**, PhD student in Natural Language Processing, University of Tehran
[LinkedIn](https://www.linkedin.com/in/keyvan-mahmoudi-7b3280103) · [Hugging Face](https://huggingface.co/KeyvanMahmoudi)

## License

The code in this repository is released under the [MIT License](LICENSE). The files in `dataset/` are widely used public teaching datasets that remain under the terms of their original sources and are not covered by this license.
