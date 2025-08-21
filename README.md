# Hands-on Hypothesis Testing
This repository contains mini-projects that I worked on to consolidate my knowledge on hypothesis testing.

## Summary for Future Reference
| Test Name                | Use Case                                         | Data Type                         | Notes                                      |
|-----------------------------|------------------------------------------------------|----------------------------------------|------------------------------------------------|
| One-sample t-test           | Compare sample mean to known population mean         | One numerical variable                 | Assumes normal distribution                    |
| Two-sample t-test           | Compare means between two independent groups         | Numerical, two groups                  | Use Welch’s t-test if variances unequal        |
| Paired t-test               | Compare means before/after (same subjects)           | Numerical, paired samples              | Repeated measures                              |
| Z-test for proportions      | Compare sample proportion to population proportion   | Categorical (binary)                   | Large sample size                              |
| Two-proportion z-test       | Compare proportions between two independent groups   | Categorical (binary)                   | Large samples                                  |
| Chi-square test             | Test association between two categorical variables   | Categorical                            | For contingency tables                         |
| ANOVA                       | Compare means among 3+ groups                        | Numerical with categorical groups      | Assumes equal variances                        |
| Mann-Whitney U test         | Compare medians of two independent groups            | Numerical, not normally distributed    | Non-parametric                                 |
| Wilcoxon signed-rank test   | Compare paired samples (non-parametric)              | Numerical, paired data                 | Alternative to paired t-test                   |

