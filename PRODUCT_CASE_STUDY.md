# Product Pulse — Product Analytics Case Study

## Project summary

**Product Pulse** is an interactive product analytics dashboard built in Tableau Public. It brings together acquisition, activation, engagement, retention, and conversion views to support product-performance reviews.

**Live dashboard:** https://public.tableau.com/app/profile/sahana.madhavan/viz/ProductPulse/ProductPulse

## Problem statement

Product teams need to understand not only how many users arrive, but also whether they activate, return, engage with important areas of the product, and progress through a conversion funnel. When these metrics are reviewed separately, it can be difficult to identify where further investigation is most valuable.

## Objective

Build an exploratory dashboard that enables product stakeholders to:

1. Compare activation across acquisition channels.
2. Observe engagement trends such as monthly active users (MAU).
3. Examine retention by cohort.
4. Explore funnel progression and potential drop-off points.
5. Segment patterns by device and time period.

## Approach

### 1. Define product questions

Start with the user journey: acquisition → activation → engagement → retention → conversion. Each dashboard section addresses a product question rather than displaying metrics without context.

### 2. Organize analysis in Tableau

The project includes dashboard views for activation by channel, cohort retention, MAU, a retention heatmap, device breakdown, funnel performance, and top pages. Date filters support exploration across time periods.

### 3. Enable interactive investigation

Stakeholders can use the available dashboard filters and visual comparisons to identify segments or stages that deserve closer examination.

### 4. Translate patterns into follow-up decisions

The dashboard is a starting point for prioritizing investigation. For example, a comparatively low activation rate in one channel would motivate reviewing traffic quality and onboarding behavior before deciding on a product change.

## Example product decision framework

| Observation to investigate | Follow-up question | Potential next action |
| --- | --- | --- |
| Channel activation differs | Are differences driven by audience or onboarding? | Compare channel cohorts and onboarding steps |
| A funnel stage shows drop-off | What friction occurs at that step? | Review user journeys and instrument step-level events |
| Cohort retention varies | Is this linked to acquisition mix or product experience? | Compare matched cohorts and usage patterns |
| Engagement changes over time | Did user mix or product behavior change? | Segment MAU and top-page trends |
| Device performance differs | Is there a usability or measurement difference? | Audit device-specific experience and event tracking |

*These are analytical examples, not verified findings from the dashboard.*

## Deliverable

An interactive Tableau Public dashboard suitable for product reviews and portfolio demonstrations.

## Skills demonstrated

- Product metric selection and framing
- Dashboard design and Tableau visualization
- Acquisition, activation, engagement, retention, and funnel analysis
- Cohort and segment-based investigation
- Product decision communication

## Limitations and next steps

- Specific metric values and trends should be transcribed only after checking the published dashboard.
- Descriptive analytics alone cannot establish causality.
- Data definitions, dataset provenance, and calculation logic should be documented alongside a shareable workbook or data dictionary.
- Future improvements could include a validated KPI glossary, annotated insights, and explicit product recommendations supported by measured results.
