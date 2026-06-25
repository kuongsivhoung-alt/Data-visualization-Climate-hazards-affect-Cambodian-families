# Climate Hazards in Cambodia (2014-2019)

## Project Overview
This project visualizes the correlation between climate-related hazards (floods, droughts, and storms) and their impact on Cambodian families. By analyzing spatial and temporal trends, this dashboard aims to support data-driven decision-making for agricultural resilience and disaster mitigation.

## Key Insights
* **Most Affected Region:** **Pailin** is identified as the most severely affected province, exhibiting the highest vulnerability index and impact frequency over the observed period.
* **Dominant Hazard:** **Drought** has consistently been the primary driver of livelihood disruption and agricultural instability for Cambodian families over the past 9 years.

## Tech Stack
* **Visualization Tool:** Tableau 
* **Data Processing:** Excel (Data Cleaning, Long-format Transformation)
  - composite_IV max-min scaling: this column has range -2.8- 0.9. Max-min scaling was used to make this data more readable, scale to range 0-1
* **Data Sources:** * [Open Development Cambodia (ODC)](https://opendevelopmentcambodia.net/)
    * [World Bank Climate Change Knowledge Portal (CCKP)](https://climateknowledgeportal.worldbank.org/)

## Dashboard Features
* **Geospatial Analysis:** Choropleth map highlighting Pailin and other high-risk provinces.
* **Hazard Impact Comparison:** Stacked bar charts demonstrating the overwhelming impact of drought compared to floods and storms.
* **Interactive Design:** Dynamic filtering allows users to isolate data for specific provinces to examine their unique hazard profiles over time.

## Methodology
1. **Data Cleaning:** Standardized raw datasets, unified province naming conventions, and transformed wide data into long-format for time-series analysis.
2. **Advanced Calculations:** Utilized LOD expressions to dynamically identify the most severe hazard per region per year.
3. **Visualization Principles:** Applied a "Left Map, Right Chart" layout to facilitate cognitive flow from geographical context to statistical evidence.

## How to View
* The source dashboard file (.twbx) is available in this repository for local viewing.
