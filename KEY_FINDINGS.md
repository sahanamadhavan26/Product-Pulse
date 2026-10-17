# Product Pulse — Evidence-Based Findings

[Explore the interactive dashboard](https://public.tableau.com/app/profile/sahana.madhavan/viz/ProductPulse/ProductPulse)

**Dataset:** Synthetic case-study data, January–August 2026. The figures below are transcribed from the two user-provided Tableau dashboard screenshots. They are descriptive, not causal results.

## Executive metrics

| Metric | Value |
| --- | ---: |
| Total users | 6,000 |
| Activation rate | 53.6% |
| Week 4 retention | 19.4% |
| Paid conversion rate | 9.0% |

## Finding 1 — Mobile activation is lower across all channels

Overall 7-day activation: **62.9% desktop vs 47.0% mobile**, a **15.9 percentage-point gap**.

| Acquisition channel | Desktop | Mobile | Gap (percentage points) |
| --- | ---: | ---: | ---: |
| Organic Search | 60.8% | 44.0% | 16.8 |
| Paid Search | 59.4% | 43.4% | 16.0 |
| Referral | 68.0% | 54.4% | 13.6 |
| Social | 63.4% | 46.6% | 16.8 |

**Interpretation:** Mobile activation is lower in each displayed acquisition channel. The comparison does not establish that the mobile interface causes the difference.

**Proposed experiment:** Test a shorter mobile onboarding flow. Measure **7-day activation** as the primary outcome, with **Week 4 retention** and **30-day paid conversion** as guardrails. **This experiment has not been run.**

## Finding 2 — Template use is associated with higher retention

| User segment | Week 4 retention | Displayed sample size |
| --- | ---: | ---: |
| Used templates | 34.1% | 1,924 |
| Did not use templates | 12.4% | 4,076 |

**Observed difference:** **21.7 percentage points**. The displayed retention rate is about 2.75 times as high for template users.

**Interpretation:** This is an association in synthetic data. Users who choose templates may differ in intent, activity, or other characteristics; the chart cannot establish that templates caused higher retention.

**Proposed investigation:** Compare users with similar characteristics, verify when template use occurs relative to retention measurement, and consider a controlled experiment if appropriate.

## Finding 3 — Referral has the highest overall channel activation

| Channel | 7-day activation |
| --- | ---: |
| Organic Search | 50.7% |
| Paid Search | 50.1% |
| Referral | 60.1% |
| Social | 53.5% |

Referral exceeds Paid Search by **10.0 percentage points**. Before adjusting acquisition spend, evaluate channel sample sizes, cost, downstream retention, and conversion.

## Finding 4 — Retention varies by signup cohort

The overview cohort heatmap shows **April** with the highest displayed Week 4 retention (**22.2%**) and **February** with the lowest (**17.3%**), a **4.9 percentage-point difference**. Cohort composition and sample sizes should be checked before interpreting why.

## Prioritized product follow-ups

1. **Mobile onboarding:** Validate the persistent device activation gap and test a shorter flow.
2. **Template experience:** Investigate the association between template usage and retention without assuming causality.
3. **Acquisition quality:** Evaluate Referral against other channels on downstream outcomes and cost.
4. **Cohort retention:** Explore the differences in signup-cohort behavior.

## Evidence and limitations

- Sources: screenshots of the **Activation & Retention** and **Product Deep Dive** dashboards.
- Synthetic data only; no real customer outcomes are claimed.
- Dashboard values have not been independently recomputed from the underlying dataset.
- No experiment was run and no improvement is claimed.
