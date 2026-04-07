# Strategic Analysis of Lithuanian Higher Education Admissions (2024-2025)

## Project Overview
This repository contains a comprehensive **Exploratory Data Analysis (EDA)** of the Lithuanian higher education admissions landscape, focusing on the "Main Admission" cycles for 2024 and 2025. 
The project utilizes **SQL-based data extraction** and Python visualization to identify growth momentum, competitive shifts, and regional opportunities, specifically for **ISM University of Management and Economics**.

The primary objective is to transform raw admissions data into **actionable marketing and recruitment strategies** for the upcoming 2026 cycle.

## Key Strategic Findings
1. Unique "Boutique" Market Positioning<br/>
   Analysis of the 2024 baseline reveals that ISM University occupies a distinct niche in the Lithuanian market.
    * High Selectivity: Maintains a low invitation rate of approximately **25%**.
    * Exceptional Yield: Achieves a nearly **90% sign rate**, the highest among major institutions.
    * Conclusion: ISM functions as a "boutique" institution where admitted students demonstrate intense brand loyalty and high motivation to enroll.

2. Robust Growth Momentum<br/>
   Despite its specialized nature, ISM is outpacing many public giants in growth speed.
    * Total unique applicants expanded by **18.9%** year-over-year, jumping from 878 in 2024 to **1,044 in 2025**.
    * This growth suggests that ISM's "premium" positioning is resonating increasingly well with the market.

3. The Competitive Lead in Economics<br/>
   The data identifies a critical "conquesting" opportunity against traditional public competitors like KTU.
    * ISM Surge: Economics applicants grew by **45%** (from 187 to 272).
    * Competitor Decline: During the same period, interest in Economics at KTU saw a noticeable decline.
    * Strategy: ISM is successfully migrating students away from traditional public tech-university programs toward its specialized curriculum.

4. Regional Breakthrough: The "Klaipėda Model"<br/>
   By comparing 2024 and 2025 regional data, a clear breakthrough was identified in the coastal region.
    * Klaipėda: Applicant volume increased by **133%**.
    * Opportunity: While Klaipėda thrived, other regions like Šiauliai saw stagnation, providing a clear roadmap to replicate successful coastal marketing tactics in other underperforming territories.

## Technical Stack & Methodology
* Data Extraction: Utilized `duckdb` to perform complex SQL joins across `applications`, `profiles`, and `programs` tables directly from a database file.
* Data Processing: `pandas` for multi-year trend analysis, conditional formatting (background gradients), and filtering for "Main Admission" stages.
* Visualization:
  * `seaborn` and `matplotlib` for creating strategic visuals.
  * Selectivity Scatterplots to map institutional yield.
  * Time-series Line Plots to track program-specific demand.
  * Geographic Heatmaps (via table gradients) to identify feeder school pipelines.

## High-Intent Pipeline Analysis
The analysis identifies specific "feeder" schools that act as high-concentration hubs for ISM.
* Volume Leaders: Kauno „Saulės“ gimnazija (63 applicants) and VDU „Rasos“ gimnazija (53 applicants) provide the highest absolute volume.
* Quality Leaders: Vilniaus licėjus serves as a premier pipeline with a 50% invitation rate.
* Program Specialists: Vilniaus „Sostinės“ and Abraomo Kulviečio gymnasiums show economics interest rates (17-18%) that significantly exceed national averages.

## Recommended 2026 Strategy
1. Replicate Success: Analyze and export the digital/event tactics used in Klaipėda to Šiauliai and Panevėžys to fix regional stagnation.
2. Target Competitor Weakness: Increase digital advertising spend in the Kaunas region targeting "Economics" keywords to capture the audience migrating away from traditional public institutions.
3. Maintain Premium High-Touch: As applicant volume scales toward 1,100+, ensure the "conversion funnel" maintains personalized communication to protect the current 90% sign rate.
