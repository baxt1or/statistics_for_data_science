# Statistics for Data Science

## 1. Foundations of Statistics

### 1.1 Understanding the Basics of Statistics
- **Descriptive Statistics**:
  - Measures of central tendency: mean, median, mode.
  - Measures of spread: variance, standard deviation, range.
  - Measures of shape: skewness, kurtosis.
- **Types of Data**:
  - Quantitative vs. qualitative.
  - Continuous vs. discrete.
  - Nominal vs. ordinal vs. interval vs. ratio.
- **Types of Variables**:
  - Dependent and independent variables.
  - Categorical: nominal, ordinal.
  - Numerical: discrete, continuous.

### 1.2 Probability Basics
- **Probability Theory**:
  - Basic principles: sample space, events.
  - Probability rules: addition rule, multiplication rule.
- **Conditional Probability**:
  - Bayes' theorem, independence of events.
- **Combinatorics**:
  - Permutations, combinations, counting methods.

---

## 2. Probability Distributions

### 2.1 Discrete Probability Distributions
- **Binomial Distribution**: When to use, formula, and properties.
- **Poisson Distribution**: For rare events occurring in fixed intervals.
- **Geometric Distribution**: Number of trials until the first success.
- **Negative Binomial Distribution**: Generalization of the geometric distribution.

### 2.2 Continuous Probability Distributions
- **Normal Distribution**: Properties, standard normal distribution (Z-scores), central limit theorem.
- **Exponential Distribution**: For time between events in a Poisson process.
- **Uniform Distribution**: Every outcome in a range has equal probability.
- **Gamma Distribution**: A generalization of the exponential distribution.
- **Beta Distribution**: For probabilities between 0 and 1.
- **Log-normal Distribution**: Used for modeling financial data and other multiplicative processes.

### 2.3 Other Distributions
- **Student's t-distribution**: Used for small sample sizes and when population standard deviation is unknown.
- **Chi-square Distribution**: Used in hypothesis testing, particularly for categorical data.
- **F-distribution**: Used in variance analysis, such as ANOVA.

---

## 3. Sampling and Estimation

### 3.1 Sampling Theory
- **Random Sampling**:
  - Importance of randomness.
  - Simple random sample, stratified sampling, cluster sampling, systematic sampling.
- **Sampling Distribution**:
  - The distribution of sample statistics (mean, variance) from repeated sampling.
- **Central Limit Theorem**:
  - Why the sampling distribution of the sample mean is normal, even for non-normally distributed populations.
- **Standard Error**:
  - Estimation of the standard deviation of the sampling distribution.

### 3.2 Point Estimation
- **Estimators**:
  - Methods for estimating population parameters (mean, variance, proportion).
- **Bias and Efficiency**:
  - The concepts of unbiased estimators and minimum variance estimators.

### 3.3 Confidence Intervals
- **Confidence Interval for the Mean**:
  - With known and unknown population variance.
- **Confidence Interval for Proportions**:
  - For categorical data.
- **Interpretation**:
  - How to interpret a confidence interval and its relationship with confidence levels.

---

## 4. Hypothesis Testing

### 4.1 Basic Concepts of Hypothesis Testing
- **Null and Alternative Hypotheses**:
  - What they represent, formulation of hypotheses.
- **Test Statistics**:
  - Z-test, t-test, chi-square test, F-test.
- **Type I and Type II Errors**:
  - False positives and false negatives.
- **Significance Level (α)**:
  - Common values like 0.05, 0.01, and 0.10.
- **P-value**:
  - How to interpret the p-value and its relationship to the significance level.
- **Power of the Test**:
  - The probability of correctly rejecting the null hypothesis.

### 4.2 One-Sample Hypothesis Tests
- **Z-test for Mean**: For large samples or known population variance.
- **t-test for Mean**: For small samples with unknown population variance.
- **Tests for Proportions**: Using Z-tests for proportions.

### 4.3 Two-Sample Hypothesis Tests
- **Independent t-test**: Comparing means of two independent groups.
- **Paired t-test**: Comparing means of two related groups.
- **Test for Differences in Proportions**: Comparing two categorical variables.

### 4.4 Chi-Square Tests
- **Goodness of Fit**: Testing if an observed frequency distribution matches an expected one.
- **Test of Independence**: Testing if two categorical variables are independent.

### 4.5 ANOVA (Analysis of Variance)
- **One-Way ANOVA**: Testing differences in means among multiple groups.
- **Two-Way ANOVA**: With two independent variables.

### 4.6 Non-Parametric Tests
- **Mann-Whitney U Test**: A non-parametric alternative to the independent t-test.
- **Wilcoxon Signed-Rank Test**: A non-parametric alternative to the paired t-test.
- **Kruskal-Wallis Test**: Non-parametric version of one-way ANOVA.

---

## 5. Regression and Correlation

### 5.1 Linear Regression
- **Simple Linear Regression**: Relationship between a dependent and an independent variable.
- **Multiple Linear Regression**: Multiple predictors and interpretation of coefficients.
- **Assumptions of Linear Regression**:
  - Linearity, independence, homoscedasticity, normality.
- **Least Squares Estimation**:
  - Minimizing the sum of squared errors.

### 5.2 Model Evaluation for Regression
- **R-squared**: How well the model fits the data.
- **Adjusted R-squared**: For multiple predictors.
- **Mean Squared Error (MSE) and Root Mean Squared Error (RMSE)**:
  - Measuring the accuracy of regression models.
- **Residual Analysis**: Checking residuals for randomness and independence.

### 5.3 Logistic Regression
- **Binary Logistic Regression**: Predicting binary outcomes.
- **Multinomial Logistic Regression**: For multi-class classification problems.
- **Odds Ratios and Interpreting Coefficients**: For binary classification.

### 5.4 Correlation
- **Pearson's Correlation Coefficient**: Measuring the linear relationship between two continuous variables.
- **Spearman's Rank Correlation**: Non-parametric measure of association.
- **Kendall’s Tau**: Another non-parametric method of association.
