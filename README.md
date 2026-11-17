# DataFlow Customer Retention Analysis

## Overview

This project uses statistical inference to evaluate whether a new customer onboarding program improves three-month retention at DataFlow, a SaaS company providing data visualization tools.

The analysis compares traditional onboarding with a new onboarding approach using confidence intervals and a two-proportion z-test.

## Technologies

- Python
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Jupyter Notebook

## Dataset

| Onboarding Program | Retained Customers | Total Customers | Retention Rate |
|---|---:|---:|---:|
| Traditional | 180 | 240 | 75.00% |
| New | 210 | 260 | 80.77% |

## Methodology

1. Calculate retention rates for both onboarding programs.
2. Construct 95% confidence intervals for each proportion.
3. Visualize and compare the confidence intervals.
4. Conduct a two-proportion z-test.
5. Estimate the potential business impact of improved retention.

## Results

- **Observed retention improvement:** 5.77 percentage points
- **Z-statistic:** -1.5558
- **P-value:** 0.1197
- **Additional retained customers per 1,000:** Approximately 58
- **Potential additional monthly revenue per 1,000 customers:** $5,769.23

## Conclusion

The new onboarding program demonstrated a higher observed retention rate than the traditional approach. However, the difference was not statistically significant at the 0.05 significance level.

Although the results suggest a potentially valuable improvement, additional data would be needed before confidently recommending a company-wide rollout.

The revenue estimate represents a hypothetical projection based on the observed difference, not a statistically confirmed financial gain.