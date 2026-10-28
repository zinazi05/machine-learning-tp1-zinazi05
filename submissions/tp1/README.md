# ML Practical Session 1 - Data Exploration and Preprocessing

**Exercise 1 — Tabular data and splits (Iris).** Loaded and inspected the dataset, selected features, and split it 80/20 with a fixed seed and stratification. 
*Benefit:* a reproducible train/test split that keeps the test set untouched for the final evaluation.

**Exercise 2 — Text data.** Read a text file line by line and loaded the 20 Newsgroups dataset to inspect its documents, labels and class names. 
*Benefit:* understanding how text data and its labels are structured before any modelling.

**Exercise 3 — Missing values (employees).** Counted and visualized missing values, converted placeholders like `'-'` and `'na'` to `np.nan`, then imputed with `SimpleImputer` (fitted on training data only). 
*Benefit:* clean, complete data without data leakage, and awareness of imputation's limits.

**Run:** put the data files next to the notebooks, install `pandas numpy scikit-learn seaborn matplotlib jupyter`, then Run All.
