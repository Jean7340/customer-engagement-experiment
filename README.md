# Customer Engagement Experiment for Direct-Mail Campaigns

A consulting-style marketing analytics project evaluating two Medicare direct-mail campaign concepts through a randomized A/B experiment involving 1,000 respondents.

> **Note:** This repository is adapted from a graduate consulting-style team project. The analysis and documentation focus on my individual analytical contributions.

---

## Business Problem

MVP Health Care wanted to determine which direct-mail campaign concept would generate stronger customer engagement before launching a large-scale Medicare campaign.

<div align="center">
<img src="figures/campaign%20concepts%20comparison.png" width="900">
</div>

---

## Experiment Design

| Sample | Experiment | Primary Metrics | Statistical Methods |
|:-------:|:----------:|:---------------:|:-------------------:|
| **1,000 respondents** | Randomized A/B Experiment | Likelihood to Open<br>Likelihood to Take Next Step | Independent-sample t-test<br>Two-proportion z-test |

---

## My Contributions

• Cleaned and validated survey data
• Conducted statistical hypothesis testing
• Built Python visualizations
• Developed business recommendations
• Presented findings to client stakeholders

---

## Key Findings

### Higher Mail-Open Intent

Option A generated significantly stronger initial customer engagement (+8.6 percentage points, p = 0.005).

<div align="center">
<img src="figures/high_open_intent_by_campaign_version.png" width="850">
</div>

---

### Funnel Insight

Although Option A attracted more attention, both campaigns produced nearly identical willingness to take the next step after reading the mail.

This suggests that the primary opportunity lies in improving:

- Message clarity
- Benefit communication
- Call-to-action (CTA)

rather than redesigning the overall campaign concept.

---

## Business Recommendations

Based on the analysis, we recommended adopting **Option A** while improving conversion-oriented elements inside the mail piece.

Suggested improvements included:

- Strengthen benefit hierarchy
- Simplify customer messaging
- Make the CTA more specific and action-oriented
- Tailor messaging for different demographic segments

---

## Skills Demonstrated

![A/B Testing](https://img.shields.io/badge/A%2FB_Testing-4CAF50?style=flat-square)
![Marketing Analytics](https://img.shields.io/badge/Marketing_Analytics-2563EB?style=flat-square)
![Statistical Testing](https://img.shields.io/badge/Statistical_Testing-7C3AED?style=flat-square)
![Customer Insights](https://img.shields.io/badge/Customer_Insights-F59E0B?style=flat-square)
![Client Presentation](https://img.shields.io/badge/Client_Presentation-DC2626?style=flat-square)

---

## Repository Structure

```
├── data/
├── images/
├── notebook/
├── README.md
```
