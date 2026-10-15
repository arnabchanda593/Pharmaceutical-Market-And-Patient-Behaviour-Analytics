# Pharmaceutical-Market-And-Patient-Behaviour-Analytics
# Pharmaceutical Market & Patient Behavior Analytics

## Project Overview

This project analyzes pharmaceutical prescription data to evaluate brand performance, patient behavior, physician prescribing patterns, and geographical market trends. The objective is to generate actionable insights that support pharmaceutical market assessment, patient segmentation, and data-driven commercial decision-making.

The analysis focuses on Brand X, examining prescription share, patient adoption, brand switching, and competitive performance.

## Objectives

- Analyze pharmaceutical prescription volume and brand performance.
- Calculate Brand X prescription share.
- Segment patients based on brand adoption and switching behavior.
- Evaluate physician prescribing patterns and specialty-level performance, where available.
- Compare brand performance across geographical territories.
- Explore patient affordability and refill patterns, where data is available.
- Translate analytical findings into actionable business insights.

## Dataset Description

The project uses a relational dataset consisting of five tables.

| Table | Records | Description |
|---|---:|---|
| Prescriptions | 39,963 | Prescription-level records |
| Patients | 5,000 | Patient-level information |
| Physicians | 260 | Physician information |
| Drugs | 4 | Drug and brand information |
| Territories | 10 | Geographical territory information |

**Data Period:** January 1, 2024 – September 20, 2025

## Tools & Technologies

- **SQL / MySQL:** Data querying, filtering, aggregation, and analysis.
- **Microsoft Excel:** Data validation, exploratory analysis, and calculations.
- **Power BI:** Interactive dashboards, KPI tracking, and visualization.
- **Python:** Data analysis and exploratory analytics, if used.

## Key Performance Indicators (KPIs)

- Total prescriptions (TRx)
- Brand X prescription volume
- Brand X prescription share
- Patient adoption and switching patterns
- Physician-level prescribing performance
- Territory-level prescription performance
- Patient copayment and refill patterns, where available

## Key Finding

Brand X accounted for 19,328 out of 39,963 prescriptions, representing approximately **48.4% of total prescriptions** in the analyzed dataset.

**Formula:**

Brand X Prescription Share = (Brand X Prescriptions / Total Prescriptions) × 100

This metric measures Brand X's share of prescriptions within the analyzed dataset and should not be interpreted as actual market-wide share unless the dataset represents the complete relevant market.

## Patient Segmentation

Patients are classified into the following segments based on prescription history and the analytical classification rules:

- **NAIVE_BRAND_X:** Patients initiating Brand X without a previously recorded Brand X prescription.
- **SWITCH_TO_BRAND_X:** Patients transitioning from another brand to Brand X.
- **SWITCH_FROM_BRAND_X:** Patients transitioning from Brand X to another brand.
- **STAY_COMPETITOR:** Patients continuing with a competing brand.

This segmentation helps distinguish new brand adoption, switching behavior, and continued competitor use.

## Dashboard Structure

### 1. Executive Overview
- Total prescriptions and Brand X prescriptions
- Brand X prescription share
- Prescription trends over time
- Overall brand performance indicators

### 2. Patient Analytics
- Patient segmentation
- Brand adoption and switching patterns
- Prescription history analysis
- Copayment and refill analysis, where available

### 3. Physician Analytics
- Prescription volume by physician
- Brand X prescribing patterns
- Physician-level brand performance
- Specialty-level comparisons, where available

### 4. Territory & Competitive Analytics
- Prescription volume by territory
- Brand performance comparisons
- Competitive prescription analysis
- Identification of territories with potential growth opportunities

## Business Applications

The analysis can help pharmaceutical commercial teams:

- Monitor brand performance and prescription trends.
- Understand patient adoption and switching patterns.
- Identify potential growth opportunities across territories.
- Evaluate physician prescribing behavior.
- Explore potential affordability-related barriers to treatment continuation.
- Support evidence-based commercial planning and brand strategy.

## Key Takeaways

- Brand X represents approximately 48.4% of prescriptions in the analyzed dataset.
- Patient segmentation provides insights into adoption, switching, and competitor retention.
- Physician and territory analysis helps identify differences in prescribing patterns.
- Prescription-level analytics can support pharmaceutical market research and commercial decision-making.

## Limitations

- The dataset contains four drugs and may not represent the entire pharmaceutical market.
- Prescription volume does not directly represent unique patients, sales revenue, or market share by value.
- Prescription data alone cannot establish the reasons behind brand switching or prescribing decisions.
- Findings depend on dataset coverage, data quality, and analytical assumptions.

## Future Scope

- Forecast future prescription trends.
- Analyze patient persistence and treatment discontinuation.
- Investigate factors associated with brand switching.
- Integrate pricing and sales data to estimate market share by value.
- Develop territory-level forecasting and opportunity prioritization models.

## Project Information

**Domain:** Pharmaceutical Analytics | Market Research | Patient Behavior Analytics

**Skills:** Data Analysis | SQL | Excel | Power BI | Patient Segmentation | KPI Development | Business Insights

**Project Type:** Pharmaceutical Market and Prescription Analytics

---

*Disclaimer: This project is intended for educational and analytical purposes. Brand X is used as a project label. Findings represent the analyzed dataset and should not be treated as verified market-wide estimates.*
