***Parameter Estimation from Systematically Censored Gaussian Data***

• Developed a Maximum-Likelihood-Estimation (MLE)-based statistical inference model in Python to recover ground-
truth mean vectors & covariance matrices of partially observed normally distributed data under known censoring
conditions, outperforming classical imputation baselines by 20%.
• Derived & implemented Projected Stochastic Gradient Descent (PSGD) & Stochastic Approximation Expectation
Maximisation (SAEM), combining numerical Riemann integration, exponential tilting, importance and Gibbs sampling
to cut time complexity by up to 25%.
• Incorporated feasibility stabilisation, constraint-aware initialisation & validation-based early stopping, reducing
numerical failure rate to 5% even under unknown covariance regime.
