# adcampaign-ab-test-analytics

# adcampaign-ab-test-analytics (Power BI)

## About Me
I’m Anusha, a data analyst with a strong interest in turning raw data into clear, actionable insights. I enjoy solving real business problems using analytics, visualization, and statistical reasoning. I built this project to demonstrate how I approach end‑to‑end analysis—from data preparation and KPI modeling to A/B testing and dashboard design.

Digital marketing is a space where small performance differences can translate into large budget impacts, so I wanted to create a realistic scenario that showcases my ability to evaluate efficiency, test hypotheses, and communicate results visually. I used Power BI and Microsoft Copilot throughout the workflow to accelerate exploration, validate logic, and enhance the clarity of the final dashboard.

This project reflects how I think as an analyst: structured, curious, and focused on delivering insights that help teams make confident decisions.


## Overview
This project analyzes digital advertising performance across multiple channels and two campaign variants (A and B). It focuses on media efficiency, A/B testing, and return on ad spend (ROAS), using a Power BI dashboard built on synthetic but realistic marketing data. Data taken from Kaggle and synthetic data added with AI-assisted Microsoft Copilot.

## Business Questions
1. How efficiently are we spending media budget (CPC, CPM, ROAS)?
2. Is Campaign A or B meaningfully better, statistically?
3. Which channels (Web Banner, Instagram, Email) deliver the best cost efficiency and returns?

## Dataset
- **Source:** Synthetic dataset created to mimic real-world digital ad performance.
- **Granularity:** Campaign × Channel × Week (Week 1 shown; extendable to multiple weeks).
- **Key fields:** Impressions, Clicks, Conversions, Ad_Spend, Sales, Campaign Type, Channel.

## Metrics & KPIs
- **CPC (Cost per Click)** = Ad Spend / Clicks  
- **CPM (Clicks per 1000 impressions)** = (Clicks / Impressions) * 1000  
- **ROAS (Return on Ad Spend)** = Sales / Ad Spend  
- **Conversion Rate (CVR)** = Conversions / Clicks  
- **Revenue per Conversion** = Sales / Conversions  

## Dashboard Pages
1. **Efficiency Overview**
   - Top KPIs: Ad Spend, Clicks, Impressions, CPC, CPM, ROAS
   - Channel comparison: CPC & CPM by channel
   - Campaign comparison: ROAS vs Ad Spend (A vs B)

2. **A/B Testing & Significance**
   - Campaign A vs B: CPC, CPM, ROAS, CVR
   - Statistical test: CVR significance flag (Significant / Not significant)

3. **Channel Performance**
   - Web Banner vs Instagram vs Email
   - Recommendations for budget reallocation

## Key Findings
- Campaign A and B show **no statistically significant difference** in conversion rate or ROAS.
- **Web Banner** is the most efficient channel, with stronger ROAS and competitive CPC compared to Instagram and Email.
- Optimization opportunity lies more in **channel mix** than in **creative variant**.

## How to Use
1. Open `powerbi/Marketing_AB_Test_Dashboard.pbix` in Power BI Desktop.
2. Connect/refresh the data from `data/week1_PowerBIdata.csv`.
3. Explore pages:
   - Efficiency Overview
   - A/B Testing & Significance
   - Channel Performance

## Future Extensions
- Add multi-week data for trend analysis.
- Include audience segments (device, geography, age).
- Expand A/B testing to creatives, landing pages, or bidding strategies.
