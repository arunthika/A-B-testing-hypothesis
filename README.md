# A-B-testing-hypothesis
# A/B Testing — Email Marketing Campaign

## Business Question
Does a personalised email subject line drive higher open rates?

## Hypothesis
- H0: No difference in open rates between groups
- H1: Personalised subject lines generate higher open rates

## Method
- Sample: 2,000 users (1,000 per group)
- Test: Independent samples t-test (scipy.stats)
- Significance level: α = 0.05

## Result
- Group A (Generic): ~20% open rate
- Group B (Personalised): ~27% open rate
- P-value: < 0.05 → Reject null hypothesis

## Business Recommendation
Switch to personalised subject lines — projected to increase
open rates by 35%, directly impacting campaign ROI.

## Tools
Python · Pandas · NumPy · SciPy · Matplotlib
