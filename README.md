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

**1. High Pollution Concentration in North & East India**
   
The analysis of the past six months identifies Assam, Delhi, Bihar, and Haryana as the worst-affected states in terms of air quality.

Key Contributing Factors:

Intensive industrial activity (cement and manufacturing clusters).

High vehicular density leading to persistent emissions.

Cross-border pollution from neighboring regions.

Case Highlight: Byrnihat (Assam) recorded the highest average AQI in this period, attributed to concentrated industrial hubs and cross-border pollutant inflows.

Top 5 Areas — Highest Average AQI (Dec 2024–May 2025):

Byrnihat, Assam

Delhi (Urban Cluster)

Patna, Bihar

Faridabad, Haryana

Muzaffarpur, Bihar

Bottom 5 Areas — Lowest Average AQI (Dec 2024–May 2025):

Ooty, Tamil Nadu

Coorg, Karnataka

Puducherry (Tamil Nadu border)

Mysuru, Karnataka

Coonoor, Tamil Nadu

**2. Clean Air Zones in Southern India**
   
Clean air zones are predominantly located in Tamil Nadu and Karnataka, reflecting a more favorable environmental profile.

Reasons for Better AQI:

Higher green cover acting as a natural pollutant filter.

Limited presence of heavy industry.

Effective environmental governance and pollution control measures.

Pollutant Status Overview:

PM10: Most prominent and consistent air quality concern across all states.

PM2.5: Highly common and hazardous due to fine particulate size.

SO₂, NO₂, NH₃: Minimal presence, currently lower priority pollutants.

CO: Prominent only in Karnataka.

**3. High-Risk Season (November – January)**
   
Seasonal patterns indicate that winter months pose the greatest risk to air quality:

November: Recorded as the worst month in 4 out of 10 states.

December: Highest average AQI (339) despite appearing only once — indicating severe short-term pollution spikes.

February: AQI drops sharply (average 98), signaling the onset of seasonal improvement.

**4. Weekend AQI Patterns**
   
The data reveals variations in AQI between weekdays and weekends:

Improvement on Weekends:

Delhi: Significant drop in AQI (+15 improvement) — reduced traffic, industrial activity, and construction.

Chennai, Pune, Kolkata: Minor improvements observed.

Worsening on Weekends:

Ahmedabad, Mumbai: Slight AQI increase, likely due to leisure traffic, open burning, or industrial/port operations.

**5. Bengaluru Air Quality**
   
Bengaluru continues to maintain its position among India’s cleaner metros:

Satisfactory air quality on 48 out of 61 days (78%).

Moderate air quality on 13 days (21%).

Summer months particularly favorable.

**6. Electric Vehicle (EV) States & AQI**
   
States with high EV adoption report better AQI performance:

Karnataka: AQI 62

Tamil Nadu: AQI 67

High EV states generally remain below AQI 110, compared to several other states exceeding 140–200 (Delhi, Bihar, Haryana).

Note:

While EV adoption shows correlation with improved AQI (p < 0.05), other pollution sources such as industry and construction still play dominant roles.

**7. Health Impact by Age Group**
   
Children (0–14 years):

Most vulnerable demographic.

High incidence of diarrheal diseases, respiratory infections, and asthma triggers.

Affected states: Karnataka, Kerala, Jharkhand, Assam, Chhattisgarh.

Elderly (65+ years):

Significant risk from asthma, COPD, and pneumonia.

Affected states: Karnataka, Kerala, Odisha, Uttarakhand.

**8. Market Insights**
   
High-Risk Markets (High AQI + High Population):

Delhi, Bihar, Rajasthan, Uttar Pradesh — priority areas for air quality interventions and health-related product demand.

Growth Opportunity Markets (Low AQI + High Population):

Tamil Nadu, Kerala, Karnataka — preventive care and health-conscious consumer markets.

Population–AQI Relationship:

No direct correlation observed.

Example: Maharashtra — highest population with moderate AQI (99.17).

Outliers: Himachal Pradesh (AQI 166.45, population 779) and Tripura (AQI 139.9, population 1724).

**9. Public Awareness**
    
General awareness of air pollution is high.

However, technical understanding of AQI, PM2.5, and PM10 remains low, especially among marginalized communities.

While many adopt basic protective measures, translating AQI data into actionable decisions remains limited.

**10. State-Wise Air Quality Trends**
    
Improving States:

Bihar, Uttar Pradesh, Delhi, Odisha.

Worsening States:

Maharashtra, Assam, Andhra Pradesh.

Regional Insights:

North India: Mixed — Delhi, UP, Bihar improved; Punjab, Haryana stagnant.

East India: Bihar improved; Assam and Odisha show mixed patterns.

West India: Maharashtra and Gujarat worsened.

South India: Slight deterioration in Andhra Pradesh, Telangana, Kerala.

Northeast India: Data sparse and variable — opportunity for CSR-driven monitoring initiatives.

# Recommendation and Decision 

**North India**
States Covered: Delhi, Haryana, Uttar Pradesh, Punjab, Bihar, Himachal Pradesh
AQI Range: 140–207 (Very High Pollution Levels)

**Recommended Product Features**:

Medical-grade HEPA H13/H14 filters capable of capturing PM2.5 and PM10 particles.

Activated carbon filters to remove smoke, sulfur dioxide (SO₂), nitrogen dioxide (NO₂), and unpleasant odors.

Real-time AQI display with LED indicators and mobile synchronization.

Safety features including Child Lock and Auto Mode for family protection.

High Clean Air Delivery Rate (CADR) designed for large urban rooms.

**South India**
States Covered: Karnataka, Tamil Nadu, Kerala, Telangana, Andhra Pradesh
AQI Range: Mostly below 100 (Moderate to Clean Air)

**Recommended Product Features:**

UV-C sterilization technology for killing airborne bacteria and viruses.

Anti-allergen filters targeting mold spores and dust mites.

Silent/Night mode suitable for bedrooms and children’s rooms.

Smart app control with WiFi connectivity, catering to tech-savvy urban households.

Energy-efficient designs aligned with the region’s growing green electric vehicle (EV) ecosystem.

**Eastern and Central India**
 
States Covered: Odisha, West Bengal, Assam, Jharkhand, Chhattisgarh, Bihar
AQI Range: 115–150 (Moderate to High Pollution)

**Recommended Product Features:**

Multi-layer filtration systems combining dust filters, HEPA, and activated charcoal.

Low-maintenance designs featuring longer filter life and filter health indicators.

Rugged build quality and stable power consumption for mixed rural and urban environments.

Rural-specific models offering battery backup or solar-compatible options for areas with unreliable power.

**West India**

States Covered: Maharashtra, Gujarat, Rajasthan, Goa
AQI Range: 100–130 (Urban High Pollution)

**Recommended Product Features:**

CO-specific filtration with carbon monoxide and volatile organic compound (VOC) sensors.

Industrial-strength models suitable for kitchens, workshops, and clinics.

Dual-mode operation controlling both pollution and odors.

Sleek designs with wall-mount options ideal for space-constrained apartments.

**North-East India**

States Covered: Mizoram, Manipur, Meghalaya, Tripura, Nagaland, Sikkim, Arunachal Pradesh
AQI Range: 47–90 (Mostly Clean Air)

**Recommended Product Features:**

Filtration optimized for smoke and VOCs typical of biomass cooking exposure.

Compact and portable units suitable for smaller rooms.

Low noise and low power consumption, ideal for remote or tier-3 households.

Affordable Essential Series models targeting preventive care needs.

**Ideal Air Purifier Product Features**

For broad applicability across regions and user needs, an ideal air purifier should include:

Pre-Filter: Captures large dust particles, hair, and pet dander.

HEPA Filter (H13/H14): Removes 99.97% of PM2.5, PM10, allergens, and bacteria.

Activated Carbon Filter: Absorbs VOCs, smoke, cooking odors, and harmful gases like CO and SO₂.

Real-time AQI Monitoring: Color-coded LED and numeric display for easy air quality tracking.

Silent Mode: Operates at less than 32 decibels for night-time use.

Eco Mode: Reduces power consumption for energy efficiency.

Auto Mode: Automatically adjusts fan speed based on AQI levels.

Capable of killing airborne viruses, bacteria, and mold spores.

Target Users: Ideal for households with children and elderly members, as well as institutional settings like hospitals and schools.

Cost Considerations: Should be budget-friendly without compromising essential performance features

# Conclusion 

This analysis highlights the stark regional disparities in air quality across India, with North India facing very high pollution levels, while Southern and North-Eastern regions maintain comparatively cleaner air. The findings emphasize the need for tailored air purifier solutions that address specific regional pollution profiles and user requirements. Advanced filtration technologies like HEPA, activated carbon, and UV-C sterilization are essential to effectively combat particulate matter and harmful gases. Additionally, smart features such as real-time AQI monitoring and energy-efficient modes cater to evolving consumer preferences, especially in urban areas. The project underscores the importance of integrating environmental awareness with technological innovation to improve public health outcomes. Targeted interventions, informed product design, and increased public education will be critical to mitigating pollution-related risks and enhancing quality of life across India’s diverse regions.

# References

- Public perception on occupational exposure to air pollution in India” by Abinaya Sekar, George Kuttiparichel Varghese, and
Ravi Varma [ https://doi.org/10.1177/10519815241305004 ]

- Understanding public perceptions, attitudes, and awareness of air pollution and its effects on health” by Renju Chandran,
Bindusree A.R., M.C. Sarath Chandran [ https://doi.org/10.1016/B978-0-443-23788-1.00013-0 ]

- https://www.iqair.com/in-en/india?srsltid=AfmBOoq7KjEoX15R4FyOA9o9kRPrFxt5PgvmOp6zV9VHr-KrtcTlvxAk
  
- https://www.thehindu.com/news/cities/Delhi/90-citizens-aware-of-air-pollution-but-lack-awareness-of-causes-andimpact/article25528325.ece?utm_source

- https://www.business-standard.com/india-news/air-pollution-related-terminologies-awareness-low-among-urbanpoor-study-124040700353_1.html?utm_source

- https://www.indiaspend.com/80-of-indians-polled-in-17-cities-believe-air-pollution-affects-quality-of-life-new-study

- https://www.drishtiias.com/daily-updates/daily-news-analysis/indias-progress-under-ncap?utm_source
