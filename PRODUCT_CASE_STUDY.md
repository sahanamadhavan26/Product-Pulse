# Product Pulse — Product Analytics Case Study

## Project overview

Product Pulse is an interactive **Tableau Public** product analytics case study built using **synthetic data (January–August 2026)**.

**[Open the interactive dashboard](https://public.tableau.com/app/profile/sahana.madhavan/viz/ProductPulse/ProductPulse)**

## Problem and objective

Product teams need to understand how users activate and return, and whether behavior differs across acquisition channels, devices, and product features. This dashboard brings together key metrics and segment-level comparisons to generate hypotheses for product improvements.

## Dashboard design

### Overview: Activation & Retention

- **6,000 total users**
- **53.6% activation rate**
- **19.4% Week 4 retention**
- **9.0% paid conversion rate**
- Signup-cohort retention heatmap across weeks 1–4
- Activation by device and acquisition channel
- Interactive channel and device filtering

### Deep Dive

- Desktop vs mobile 7-day activation across **Organic Search, Paid Search, Referral, and Social**
- Week 4 retention comparison for users who **used templates** versus those who **did not**

## Insights

1. **Mobile activation gap:** Desktop 7-day activation is **62.9%**, versus **47.0%** on mobile, a **15.9-point gap**. The Deep Dive shows lower mobile activation in every displayed channel, with gaps of **13.6–16.8 percentage points**.
2. **Template usage and retention:** Week 4 retention is **34.1%** among template users (n=1,924), versus **12.4%** among non-users (n=4,076). This is an **observed association**, not a causal effect.
3. **Acquisition channel:** Referral has the highest displayed overall 7-day activation rate at **60.1%**.
4. **Cohort differences:** April has the highest displayed Week 4 retention at **22.2%**, while February has the lowest at **17.3%**.

See [KEY_FINDINGS.md](KEY_FINDINGS.md) for full data tables, interpretation, and product follow-ups.

## Product recommendation

**Hypothesis:** Reducing mobile onboarding friction may improve activation.

**Proposed test:** Compare a shorter mobile onboarding flow against the existing experience.

**Primary metric:** 7-day activation.

**Guardrails:** Week 4 retention and 30-day paid conversion.

**Status:** **Proposed, not executed.** No uplift or causal improvement is claimed.

A separate investigation could examine why template users show higher observed retention, including potential selection bias.

## Skills demonstrated

- Tableau dashboard creation and visual storytelling
- KPI definition and product analytics
- Cohort, device, and acquisition-channel segmentation
- Translating observations into testable product hypotheses
- Explicit communication of assumptions and limitations

## Limitations

The dataset is synthetic. Dashboard figures were transcribed from screenshots and have not been independently audited against the underlying data. Descriptive comparisons do not establish causation.

## Artifacts

- [Live Tableau Public dashboard](https://public.tableau.com/app/profile/sahana.madhavan/viz/ProductPulse/ProductPulse)
- [Evidence-backed findings](KEY_FINDINGS.md)
- Screenshots: `screenshots/dashboard-overview.png` and `screenshots/dashboard-deep-dive.png` (to be uploaded)
- Tableau packaged workbook: not yet uploaded
