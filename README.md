# Market Fit Analysis for Air Purifier Development Using AQI and Health Impact Insights

# Introduction

This project focuses on conducting a comprehensive market fit analysis for the development of an innovative air purifier, tailored to India’s worsening air quality crisis. Using AQI data (2022–2025) alongside health impact, population, and EV adoption datasets, the study identifies key pollutants, high-risk cities, and consumer demand triggers. It also examines the correlation between pollution levels and health outcomes, and how these influence purchasing behavior. The insights are visualized through an interactive dashboard, enabling top-level management to make data-driven decisions on product features, target markets, and pricing strategies—ensuring the air purifier is both effective and aligned with market needs.

# Object 

The objective of this project is to evaluate the market potential for a new air purifier in India by integrating environmental, health, and demographic data. Specifically, it aims to:

- Identify cities and regions with the highest and most persistent air pollution levels.

- Analyze the correlation between air quality and pollution-related health outcomes.

- Determine key pollutants and essential product features for targeted filtration.

- Assess consumer demand triggers based on pollution spikes and market trends.

- Provide actionable insights through an interactive dashboard to guide product design, pricing, and marketing strategies for optimal market fit.

# Dataset 

The dataset is provided from DataFul

**AQI(2022-2025).csv** : Raw AQI data for Indian states

**Health related consequences.csv**  : Survey data on public health perception

**Population data.csv** : State wise population data

**Vehicle data.csv** : State wise all types of vehicle data  

The Additional Data got from Various Websites , blogs and reports.

# Tools Used

**Jupyter Notebook**

• Version : JupyterLab 4.0 / Notebook 7.1 (Latest release in 2025)

• Python Version : Python 3.11

• Description : Jupyter Notebook provides an interactive environment for writing and running code, visualizing data, and documenting analysis.

**Power BI Desktop**

• Version : Power BI Desktop May 2025 Update (Version 2.128.x)

Description : Power BI is a business analytics tool that enables data transformation, modeling, and rich interactive visualizations

# Analysis and Insights

**Air Quality Analysis (Dec 2024 – May 2025)**

1. High Pollution Concentration in North & East India
Worst-affected states: Assam, Delhi, Bihar, Haryana.

Top contributing factors:

Industrial activity (cement & manufacturing clusters).

High vehicular density.

Cross-border pollution.

Example: Byrnihat (Assam) tops the list, likely due to industrial hubs and cross-border inflow of pollutants.

Top 5 Areas (Highest Average AQI) (last 6 months):

Byrnihat, Assam

Delhi (urban cluster)

Patna, Bihar

Faridabad, Haryana

Muzaffarpur, Bihar

Bottom 5 Areas (Lowest Average AQI) (last 6 months):

Ooty, Tamil Nadu

Coorg, Karnataka

Puducherry, Tamil Nadu border

Mysuru, Karnataka

Coonoor, Tamil Nadu

2. **Clean Air Zones in Southern India**
   
Concentrated mainly in Tamil Nadu & Karnataka.

Reasons for better AQI:

Higher green cover.

Less heavy industry.

Effective environmental governance.

Pollutant Status:

PM10: Most prominent in all states — key air quality concern.

PM2.5: Highly common — fine particulate hazard.

SO₂, NO₂, NH₃: Minimal presence — lower risk currently.

CO: Prominent only in Karnataka.

3. **High-Risk Season (Nov – Jan)**
   
November: Appears in 4 of 10 states as the worst month.

December: Highest average AQI (339) despite appearing only once — pollution spike alarming.

February: Significant AQI drop (average 98) — start of seasonal improvement.

4. **Weekend AQI Patterns**
   
Improves on Weekends:

Delhi (+15 AQI drop) — reduced traffic & industry.

Chennai, Pune, Kolkata — minor improvements.

Worsens on Weekends:

Ahmedabad, Mumbai — slight rise, possibly due to leisure travel, open burning, or industrial/port activity.

5. **Bengaluru Air Quality**
   
Satisfactory air quality: 78% of days (48 out of 61 days).

Moderate category: 21% of days (13 days).

Remains one of India’s cleaner metros, especially in summer.

6. **Electric Vehicle (EV) States & AQI**
   
High EV states show better AQI than national averages:

Karnataka: 62

Tamil Nadu: 67

High EV group mostly stays under AQI 110.

Other states often exceed 140–200 (e.g., Delhi, Bihar, Haryana).

Note: EV adoption impact is gradual — other pollution sources still dominate.

Statistical significance: p < 0.05.

7. **Health Impact by Age Group**
   
Children (0–14 years): Most affected.

Diseases: Diarrheal illnesses, respiratory infections, asthma triggers.

States: Karnataka, Kerala, Jharkhand, Assam, Chhattisgarh.

Elderly (65+): Also high risk.

Diseases: Asthma, COPD, pneumonia.

States: Karnataka, Kerala, Odisha, Uttarakhand.

8. **Market Insights**
   
High-risk markets (High AQI + High population): Delhi, Bihar, Rajasthan, Uttar Pradesh.

Growth opportunity (Low AQI + High population): Tamil Nadu, Kerala, Karnataka — preventive care markets.

No direct AQI–population correlation:

Example: Maharashtra — highest population, moderate AQI (99.17).

Outliers: Himachal Pradesh (AQI 166.45, pop 779), Tripura (AQI 139.9, pop 1724) — small pop, poor AQI.

9. **Public Awareness**
    
Awareness of air pollution high, but low understanding of AQI, PM2.5, PM10 — especially in marginalized groups.

Many adopt basic protective measures but struggle to turn AQI data into action.

10. **State-wise Air Quality Trends**
    
Most improved: Bihar, Uttar Pradesh, Delhi, Odisha.

Worsened: Maharashtra, Assam, Andhra Pradesh.

Regional notes:

North India: Mixed — Delhi/UP/Bihar improved; Punjab/Haryana stagnant.

Eastern India: Bihar improved; Assam/Odisha mixed.

Western India: Maharashtra/Gujarat worsened.

Southern India: Mild deterioration in AP, Telangana, Kerala.

Northeast: Sparse/variable data — potential for CSR monitoring projects.


