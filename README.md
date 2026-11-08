# Machine Learning Course

Practical notebooks covering the core machine learning toolkit with scikit-learn, Keras, XGBoost and mlxtend: data preprocessing, regression, classification, clustering, dimensionality reduction, neural networks, model selection and association rule learning. The main notebook of each chapter runs on a small dataset from the [`dataset/`](dataset) folder; the numbered sub-notebooks (3.1, 4.1, 4.2) and chapter 8 are larger case studies on real-world data.

## Contents

| # | Notebook | Topics | Datasets |
|---|---|---|---|
| 1 | [Data Preprocessing](1.%20Data_Preprocessing.ipynb) | Handling missing values, train/test split, feature scaling | `Data.csv` |
| 2 | [Regression](2.%20Regression.ipynb) | Simple and multiple linear regression, backward elimination, polynomial regression, SVR, decision tree and random forest regression | `Salary_Data.csv`, `50_Startups.csv`, `Position_Salaries.csv` |
| 3 | [Classification](3.%20Classification.ipynb) | Logistic regression, k-NN, SVM, kernel SVM, Naive Bayes, decision tree and random forest classification | `Social_Network_Ads.csv`, `PastHires.csv` |
| 3.1 | [Classification case study: bank marketing](3.1%20Classification_Banking_Case_Study.ipynb) | Encoding, scaling, feature selection; outlier detection with Local Outlier Factor, One-Class SVM, Isolation Forest and Minimum Covariance Determinant; SVM, MLP, classification based on association rules (CBA), automated feature engineering (autofeat) with logistic regression | `banking.csv` * |
| 4 | [Clustering](4.%20Clustering.ipynb) | K-means (elbow method) and hierarchical clustering (dendrograms) | `Mall_Customers.csv` |
| 4.1 | [K-Means and DBSCAN](4.1%20KMeans_and_DBSCAN.ipynb) | Choosing the number of clusters with the silhouette score, K-means and density-based clustering (DBSCAN), PCA for visualization | `car_insurance.csv`, `earthquake_ir.csv` * |
| 4.2 | [Gaussian Mixture Models](4.2%20Gaussian_Mixture_EM.ipynb) | Implementing the expectation–maximization (EM) algorithm for Gaussian mixtures from scratch with NumPy; choosing the number of components with the silhouette score | `social_media_data.csv` * |
| 5 | [Dimensionality Reduction](5.%20Dimensionality_Reduction.ipynb) | PCA, LDA and kernel PCA | `Wine.csv`, `Social_Network_Ads.csv` |
| 6 | [Artificial Neural Networks](6.%20Artificial_Neural_Networks_(ANN).ipynb) | A feed-forward network for customer churn prediction with Keras | `Churn_Modelling.csv` |
| 7 | [Model Selection & Boosting](7.%20Model_Selection_&_Boosting.ipynb) | k-fold cross-validation, grid search, XGBoost | `Social_Network_Ads.csv`, `Churn_Modelling.csv` |
| 8 | [Association Rule Learning](8.%20Association_Rule_Learning.ipynb) | Frequent itemsets with Apriori and association rules (support, confidence, lift) on movie ratings | `movies.csv`, `ratings.csv` * |

\* Datasets marked with an asterisk are not included in this repository; place the file next to the notebook before running it. The `ratings.csv` and `movies.csv` files follow the format of the [MovieLens](https://grouplens.org/datasets/movielens/) dataset.

The `dataset/` folder also contains `Market_Basket_Optimisation.csv` (association rules) and `Restaurant_Reviews.tsv` (text classification) for exercises.

## Getting started

Open a notebook in Google Colab and upload the dataset it uses, or run locally:

```bash
git clone https://github.com/keyvanmahmoudi/Machine_Learning_Course.git
cd Machine_Learning_Course
pip install jupyter numpy pandas matplotlib seaborn scikit-learn statsmodels scipy keras tensorflow xgboost pydotplus mlxtend pyarc autofeat
jupyter notebook
```

Notebooks read their CSV files by file name, so either run them from the folder that contains the data or adjust the path in the loading cell (for example `dataset/Data.csv`).

## Prerequisites

Basic Python, NumPy and pandas. The companion course [Python and Data Analysis](https://github.com/keyvanmahmoudi/Python-and-data-analysis) covers these from scratch.

## Author

**Keyvan Mahmoudi**, PhD student in computer engineering, University of Tehran
[LinkedIn](https://www.linkedin.com/in/keyvan-mahmoudi-7b3280103) · [Hugging Face](https://huggingface.co/KeyvanMahmoudi)

## License

The code in this repository is released under the [MIT License](LICENSE). The files in `dataset/` are widely used public teaching datasets that remain under the terms of their original sources and are not covered by this license.
