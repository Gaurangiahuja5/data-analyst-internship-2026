# Week 4: Hypothesis Testing

This week's task was to formally test, using statistics, two patterns identified
earlier in this internship.

## What I Did

- Formulated two hypotheses based on Week 1 and Week 3 findings:
  1. Churn is related to Geography (tested with a chi-square test)
  2. Churn is related to Account Balance (tested with an independent t-test)
- Ran both tests in Python (SciPy) and interpreted the p-values against the
  standard 0.05 significance threshold
- Built two charts to visualize the data underlying each test
- Wrote up the hypotheses, test results, and interpretation in a full report

## Key Result

Both null hypotheses were rejected with extremely small p-values:
- Geography vs. churn: χ² = 300.63, p = 5.25 × 10⁻⁶⁶
- Balance vs. churn: t = 11.94, p = 1.21 × 10⁻³²

This statistically confirms that Germany's elevated churn rate and the higher
average balance of churned customers are both real, significant patterns —
not due to chance.

## Files

- `Customer_churn.ipynb` — the full analysis notebook, including Weeks 1–4
  (see the "Week 4" section within it)
