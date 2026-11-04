# Machine Learning Models — Data Preparation & Predictive Analytics

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
