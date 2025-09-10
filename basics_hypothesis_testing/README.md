# Basic Hyphotesis Testing Project

This module introduces the core ideas behind hypothesis testing, illustrated with simulations (coin flips, quiz questions, purchase rates). It explains how to formulate hypotheses, calculate p-values, and interpret results.

## Contents
- **hypo_testing_project.ipynb** → main notebook with code and explanations
- **prices.csv** → dataset for analysis
- **monthly_report.csv** → second dataset for analysis
- **README.md** → project description

## Contents: 
- Hypotheses - Definition: 
Null Hypothesis (H₀): baseline assumption, usually “no effect” or “no difference.”
Alternative Hypothesis (H₁): the competing claim that a real effect or difference exists.

- P-Values:
A p-value measures how likely the observed data would be if the null were true. Small values suggest stronger evidence against the null.

_ Significance Thresholds:
A cutoff (often 0.05) used to decide if results are “statistically significant.” If the p-value is below this level, we reject the null hypothesis.

_Error Types:
Type I Error: false positive — rejecting a true null hypothesis.
Type II Error: false negative — failing to reject a false null hypothesis.

- One-Sample T-Test:
Used when comparing the mean of a sample to an expected population mean.

- Binomial Test:
Used when comparing the observed frequency of success/failure to an expected probability.

- Multiple Testing:
Running many hypothesis tests increases the risk of false positives. Adjustments or stricter thresholds are needed when testing many hypotheses.

## How to Run
1. Open the notebook in Jupyter
2. Run the cells to reproduce the analysis