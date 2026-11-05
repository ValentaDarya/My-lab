# Machine Learning Models — Data Preparation & Predictive Analytics

## Models Used

- **Linear regression (`LinearRegression`)** — predicts the numerical price of a used car; evaluated with mean absolute error (MAE).
- **Multilayer perceptron (`MLPClassifier`)** — a neural network that predicts the car price category.
- **Decision tree (`DecisionTreeClassifier`)** — predicts the price category and provides predictions for the majority-voting comparison in `04_neural_networks.ipynb`.
- **Logistic regression (`LogisticRegression`)** — provides another price-category classifier for comparison and voting.
- **Random forest (`RandomForestClassifier`)** — explored in the separate tree and random forest notebook, `03_tree_and_random_forest.ipynb`.

## Project Objectives

- Practice an end-to-end analytical workflow, from raw vehicle data inspection to model-oriented preparation.
- Detect duplicates, missing values and outliers, and explore relationships between vehicle attributes and price.
- Apply and compare decision trees, random forests and neural-network methods in supervised learning exercises.
- Investigate feature importance and hyperparameter tuning to understand model behavior.
- Explore vehicle price prediction as a follow-up exercise; the final notebook remains an unfinished draft.

**Sources:** Original notebooks on data cleaning, visualization, decision trees, random forests, neural networks, and the final used-car-price assignment.

## Covered techniques
- Duplicate and missing-value inspection
- Exploratory plots and outlier investigation
- Feature selection and importance
- DecisionTreeClassifier and RandomForestClassifier
- Hyperparameter tuning exercises
- Logistic regression, linear regression, and MLP exercises

**Reproducibility:** Several original notebooks reference vehicle CSV files that are not included in the supplied archives. The final price-prediction notebook is partially completed; no final validated performance claim is made here.

## Synthetic demo data

The `data/vehicles_dataset.csv` and `data/vehicles_dataset_upd.csv` files, plus `vehicles_dataset_prepared.csv`, `vehicles_dataset_old.csv` and `df_out.csv`, are **synthetically generated samples**, not the original vehicle data. They are provided to demonstrate notebook workflows; metrics computed on them must not be presented as real-world model performance. Run notebooks from this folder. The final price-prediction notebook remains a draft. Dependencies include pandas, numpy, matplotlib, seaborn, scikit-learn, scipy and missingno.

## Linear Regression, Multilayer Perceptron and Decision Tree

[Notebook: 04_neural_networks.ipynb](04_neural_networks.ipynb) · [Original Google Colab notebook](https://colab.research.google.com/drive/1PpuWAfMuqVjAmKh3y6itBGZ6-Xn4U9aw?usp=sharing)

This practical assignment explores predicting used-car prices and price categories with **linear regression**, a **multilayer perceptron (MLP)**, a **decision tree**, logistic regression, and majority voting. It uses a 70/30 train/test split and evaluates predictions with MAE, accuracy, and confusion matrices.

The Colab source was compared with the repository notebook on November 5, 2026: all 50 cells have identical source text, so a duplicate notebook was not added.

**Known limitations:** The tree-model section implements `DecisionTreeClassifier`, although the assignment and voting-column label refer to a random forest. Some cells reference the undefined variable `logreg_pred`, and a prose conclusion is stored in a code cell. The notebook has not been rerun as part of this import check; saved scores are not validated performance results. The original prepared dataset is not included; the repository CSV is a synthetic demonstration sample.
