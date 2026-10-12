# Insurance Charges: End-to-End EDA

An exploratory data analysis of the insurance dataset (`insurance.csv`), ending with a list of preprocessing steps needed before modeling.

## What's covered

1. **Data quality checks**: missing and encoded-missing values, duplicates, dtype validation, constant/quasi-constant and ID-like columns, high-zero columns
2. **Univariate analysis**: summary stats, skewness/kurtosis, histograms, boxplots, frequency tables
3. **Bivariate analysis**: scatter plots, correlations, boxplots by category, grouped stats, crosstabs
4. **Multivariate analysis**: pairplot, correlation heatmap, cluster map, smoker interaction plots
5. **Outlier detection**: boxplot, IQR and Z-score methods
6. **Insights summary and preprocessing plan**

## Key findings

- The data is clean: no missing values and one duplicate row.
- `charges` is heavily right-skewed.
- Smoking status is the strongest driver of charges, and it interacts with age and BMI.
- Region has only a small effect on charges.

## Run it

```bash
pip install -r requirements.txt
jupyter notebook Full_EDA_Project.ipynb
```

`insurance.csv` (1,338 rows, 7 columns) is included in this repo and sits next to the notebook.
