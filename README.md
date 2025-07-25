# Machine Learning Algorithm Implementations

This repository contains hands-on implementations of various machine learning algorithms using Python and popular data science libraries. Each folder demonstrates a different algorithm or technique with Jupyter notebooks and example datasets.

## Project Structure

- **01_Simple_Linear_Regression/**: Implementation of simple linear regression using a real-world height and weight dataset.
- **02_Multiple_Regression/**: Implementation of multiple regression using economic data.
- **03_Polynomial_Regression/**: Implementation of polynomial regression, and notebooks for handling imbalanced datasets and missing values.
- **04_Redge_Lasso Regression/**: Implementation of Ridge, Lasso, and ElasticNet regression using the Algerian Forest Fires dataset.
- **05_Logistic_Regression/**: Implementation of binary classification using logistic regression on a synthetic dataset.

## Requirements

All notebooks require the following Python packages:

```bash
pip install -r requirements.txt
```

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Use

1. Clone the repository.
2. Install the requirements.
3. Open any notebook in Jupyter or VSCode and run the cells.

## Notebooks Overview

### 01_Simple_Linear_Regression
- `implimentation.ipynb`: Step-by-step implementation of simple linear regression on the SOCR Height-Weight dataset (`Datasets/SOCR-HeightWeight.csv`).

### 02_Multiple_Regression
- `multiple_regression.ipynb`: Multiple regression analysis on economic data (`Datasets/economic_data.csv`), including data cleaning, visualization, and model training.

### 03_Polynomial_Regression
- `polynomial_regression.ipynb`: Polynomial regression example with synthetic data (generated in-notebook).
- `Handling_imbalanced_datasets.ipynb`: Techniques for upsampling and downsampling imbalanced datasets (synthetic data generated in-notebook).
- `Handling_Missing_Value.ipynb`: Example of handling missing values using the Titanic dataset from seaborn (`sns.load_dataset('titanic')`).

### 04_Redge_Lasso Regression
- `Redge, Lasso Regression.ipynb`: Implementation of Ridge, Lasso, and ElasticNet regression on the Algerian Forest Fires dataset (`Datasets/Algerian_forest_fires_dataset_UPDATE.csv`). Includes data cleaning, exploratory data analysis, model training, and evaluation.

### 05_Logistic_Regression
- `01_Binary_Classification.ipynb`: Step-by-step implementation of binary classification using logistic regression on a synthetic dataset (generated in-notebook). Includes data generation, model training, prediction, and evaluation with accuracy, confusion matrix, and classification report.

---

Each notebook is self-contained and includes code, comments, and visualizations to help you understand the algorithm and its application. 