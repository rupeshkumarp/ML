# Machine Learning Practice Notebooks

A collection of Jupyter notebooks for learning machine learning. It covers the math and statistics behind ML, then regression, classification, ensemble methods and model evaluation, each with a small dataset.

## Repository Structure

```
ML/
├── maths/                  # Statistics & linear algebra foundations
├── regression/             # Linear regression, gradient descent, regularization
│   └── data/
├── classification/         # Logistic regression, SVM, Naive Bayes, Decision Tree
│   └── data/
├── ensemble/               # Bagging, boosting, majority voting
│   └── data/
└── model evaluation/       # Cross-validation, ROC-AUC
```

## Contents

### 1. Maths & Statistics (`maths/`)
| Notebook | Topic |
|---|---|
| `mode_median_percentale.ipynb` | Mean, median, mode, percentiles |
| `normal_distribution.ipynb`, `normal_distrubution.ipynb` | Normal distribution |
| `central_limit_therom.ipynb` | Central Limit Theorem |
| `confidence_interval.ipynb` | Confidence intervals |
| `correlation.ipynb` | Correlation |
| `modified_zscore.ipynb` | Outlier detection with modified Z-score |
| `cosine.ipynb` | Cosine similarity |
| `matrix.ipynb` | Matrix operations |
| `matplotlib_pratis.ipynb`, `pratices.ipynb` | Plotting and general practice |

### 2. Regression (`regression/`)
| Notebook | Topic |
|---|---|
| `linear_regression.ipynb` | Simple and multiple linear regression |
| `gradient_descent.ipynb` | Gradient descent from scratch |
| `train_test_split.ipynb` | Splitting data into train and test sets |
| `regualrization.ipynb` | Ridge and Lasso regularization |

**Datasets:** `home_prices.csv`, `mpg.xlsx`, `dataset.csv`

### 3. Classification (`classification/`)
| Notebook | Topic |
|---|---|
| `logistic_regression.ipynb` | Binary logistic regression |
| `multiclass_logistic_regression.ipynb` | Multiclass logistic regression |
| `svm.ipynb` | Support Vector Machines |
| `naive_bayes.ipynb` | Naive Bayes (e.g. spam detection) |
| `decision_tree.ipynb` | Decision Trees |
| `class_imbalance.ipynb` | Handling imbalanced classes (SMOTE, resampling) |

**Datasets:** `titanic.csv`, `churn.csv`, `spam.csv`, `salaries.csv`, `car_ownership.csv`, `Raisin_Dataset.xlsx`

### 4. Ensemble Methods (`ensemble/`)
| Notebook | Topic |
|---|---|
| `random_forest(bagging).ipynb` | Bagging and Random Forest |
| `boosting.ipynb` | Boosting (AdaBoost, Gradient Boosting, XGBoost) |
| `majority_voting.ipynb` | Voting classifier |

**Datasets:** `titanic.csv`, `cancer_data.csv`, `Raisin_Dataset.xlsx`, `ad_spend.csv`

### 5. Model Evaluation (`model evaluation/`)
| Notebook | Topic |
|---|---|
| `K_fold_crossvalidation.ipynb` | K-Fold cross-validation |
| `ROC_AUC.ipynb` | ROC curve and AUC score |

## Tech Stack

- Python 3
- NumPy, Pandas, SciPy
- Matplotlib, Seaborn, Plotly
- scikit-learn, XGBoost, imbalanced-learn
- mlxtend, pyfpgrowth

## Getting Started

```bash
# Clone the repo
git clone https://github.com/rupeshkumarp/ML.git
cd ML

# Install dependencies
pip install numpy pandas scipy matplotlib seaborn plotly scikit-learn xgboost imbalanced-learn mlxtend pyfpgrowth openpyxl jupyter

# Launch Jupyter
jupyter notebook
```

Open any notebook and run the cells in order. Each notebook reads its data from the `data/` folder in the same directory.

## Suggested Learning Path

1. `maths/`: statistics foundations
2. `regression/`: linear models and gradient descent
3. `classification/`: classifiers and class imbalance
4. `model evaluation/`: validating models
5. `ensemble/`: combining models for better performance

## Author

**Rupesh Kumar P** · [GitHub](https://github.com/rupeshkumarp)
