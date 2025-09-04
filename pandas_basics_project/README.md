# Pandas Basics Project

This project provides a simple data set and a Jupyter notebook demonstrating core features of the [pandas](https://pandas.pydata.org/) library. Each CSV file contains 100 rows of mock data for practice.

The notebook walks through theory notes and practical examples of:

- DataFrame creation, CSV I/O, and inspection (`head`, `info`, `describe`)
- Column/row selection, logical filtering, and `.reset_index`
- Adding/transformation of columns, `apply` with lambdas (column-wise & row-wise)
- Renaming columns, `groupby` (custom percentiles), multi-key `groupby`
- Pivot tables
- Merging (inner/left/right/outer, custom keys with `left_on`/`right_on`, suffixes) and concatenation
- Variable types & dtypes; numeric vs categorical cleanup with `.astype`
- Ordered categoricals via `pd.Categorical`
- One-hot encoding with `pd.get_dummies`
- Value replacement with `replace`
- Data summaries (central tendency, spread) and Matplotlib visuals (boxplot, histogram, bar, pie)
- Value counts and proportions
- Associations:
  - Quantitative–Categorical: boxplots, overlapping histograms (density scaling)
  - Non-binary categories: multi-group boxplots
  - Quantitative–Quantitative: scatter, covariance, Pearson correlation with p-value
  - Categorical–Categorical: contingency tables (frequencies, proportions, marginals), expected counts, Chi-square test
- Reusable helpers (`value_props`, `quick_corr`) for EDA

## Setup

Install the required Python packages before running the notebook:

```
pip install -r requirements.txt
```

Then start Jupyter to explore the notebook:

```
jupyter lab
```

## Project Structure
```
pandas_basics_project/
├── data/
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
├── pandas_basics_project.ipynb
├── requirements.txt
└── README.md
```

Open `pandas_basics_project.ipynb` to run through the examples.
