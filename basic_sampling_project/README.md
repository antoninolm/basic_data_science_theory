# Basic Sampling Project

This project explores sampling techniques using Python and Jupyter notebooks.

## Contents
- **basic_sampling_project.ipynb** → main notebook with code and explanations
- **salmon_population.csv** → dataset for analysis
- **README.md** → project description

## Contents: 
- Sampling from a Population: Samples are used to estimate characteristics of larger populations. Since full population data is often unavailable, researchers rely on sample statistics like the mean or median to approximate population values.
- Random Sampling in Python: With tools such as np.random.choice(), we can simulate random draws from a dataset. This allows us to generate samples, calculate their means, and compare them against the known population mean.
- Sampling Distributions: A sampling distribution shows how a statistic (like the mean) behaves across many repeated samples. It illustrates the natural variability in sample estimates and helps us understand uncertainty in our measurements.
- Central Limit Theorem (CLT): The CLT explains that, with sufficiently large samples, the distribution of sample means becomes approximately normal, even if the population itself is skewed. The average of the sample means aligns with the true population mean, and the spread becomes smaller as sample size grows.
- Standard Error: The standard error describes how much sample means are expected to vary from the population mean. Larger samples make this error smaller, while populations with greater variability make it larger.
- Biased vs. Unbiased Estimators: A statistic is called unbiased if, on average, it equals the true population parameter. The sample mean is an unbiased estimator of the population mean. Other statistics, such as the maximum, are biased because their averages do not align with the population value.
- Using the Normal CDF: The cumulative distribution function of the normal curve lets us calculate probabilities about sample means. By combining the CLT with this tool, we can answer questions such as: What is the chance that a group of fish has an average weight below a certain threshold?

## How to Run
1. Open the notebook in Jupyter
2. Run the cells to reproduce the analysis

