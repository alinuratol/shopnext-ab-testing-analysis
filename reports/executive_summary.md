# Executive Summary

### Simulated experiment result
- **Sample:** 12,000 unique users; A 6,000, B 6,000.
- **Conversion:** A 10.62%, B 10.75%; absolute lift +0.13 pp (+1.26% relative).
- **Conversion inference:** z-test p=0.8131; 95% effect CI [-0.97, +1.24] pp.
- **Revenue per user:** A 2,230 KZT, B 2,125 KZT; Welch p=0.5299; bootstrap 95% CI for B−A [-426, 211] KZT.
- **SRM diagnostic:** p=1 with expected 50:50 allocation.
- **Recommendation:** Do not claim an uplift; retain control and consider a powered follow-up.
- **Limitations:** synthetic data, no registration or guardrail margins, exploratory segment tests, possible outlier sensitivity.

## Suggested next steps

1. Validate assignment and data collection with engineering.
2. Agree on guardrail margins, baseline and MDE before the next experiment.
3. Repeat the analysis on production data using a pre-registered plan.
