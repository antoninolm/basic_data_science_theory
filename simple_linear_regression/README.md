Basic Concept: Regression fits a line to describe and predict the relationship between variables.

Equation of a Line: Defined by slope and intercept, showing how changes in predictors affect outcomes.

Best Fit Line (OLS): Ordinary Least Squares minimizes the squared residuals to find the optimal line.

Fitting in Python: Using statsmodels.OLS.from_formula(), regression models can be built and coefficients extracted.

Prediction: Once fitted, models can generate outcome estimates for new input values.

Interpretation: The intercept is the expected value when predictors are zero; the slope shows how outcomes change per unit of predictor.

Residual Analysis: Fitted values and residuals help check model accuracy and assumptions.

Assumptions: Key assumptions include normality (residuals are normally distributed) and homoscedasticity (constant variance).

Categorical Predictors: Regression can also handle binary predictors, where the intercept gives the mean of the reference group and the slope reflects the difference between categories.
