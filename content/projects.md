+++
draft = false
title = 'Projects'
+++

At the University of Chicago, I have developed my technical skillset through both coursework and extracurricular projects. 

---

## Course Projects
*Projects where I collaborated with classmates to analyze social issues.*

### Project All Access Livable Housing: Housing and Homelessness in San Francisco  
**Tools:** Python (Pandas, Plotly Dash, Altair)  
**Links:** [GitHub Repo](https://github.com/uchicago-2026-capp30122/project-all-access-livable-housing)  
*Course: Computer Science with Applications II*

**The Overview** Working in a team of four, we built an end-to-end data application to analyze housing and homelessness trends in San Francisco. The project is powered by a Python pipeline that ingests and standardizes disparate public datasets and ultimately produces a multi-dimensional analysis of relevant indicators, with a dynamic choropleth map and line graphs visualizing covariates such as eviction rates, rent levels, encampment counts, and 311 service calls.  

**My Personal Contributions**
* **Data Engineering Pipeline:** Built a robust ingestion and cleaning pipeline for three primary datasets (median rent, encampment counts, and 311 service calls).
    * *Temporal Interpolation:* Harmonized inconsistent reporting cycles using linear interpolation to create a continuous, high-frequency time-series for trend analysis.
    * *Spatial Crosswalking:* Engineered a ZIP-to-census-tract mapping pipeline, utilizing weighted population aggregations to ensure granular data alignment across disparate geographic levels.
    * *Statistical Imputation:* Addressed missing data by implementing mean imputation across feature sets, maintaining sample size integrity and ensuring model robustness for downstream analysis.
* **Data Visualization:** Developed interactive line graphs visualizing how monthly median rent, encampment distributions, and street homeless population estimates change over time in different geographic locations (zip codes and census tracts).
* **UX & Design Leadership:** Led the dashboard interface design and authored textual content to ensure technical findings were accessible to policy stakeholders.

---

### Identifying Neighborhoods in Chicago at Risk of Gentrification
**Tools:** ArcGIS  
*Course: GIS Applications in the Social Sciences*

**The Overview** Working with a teammate, we developed a spatial analysis model to identify Chicago census tracts most at risk of gentrification. Rather than relying on a single indicator, we implemented a composite indexing framework that synthesized market pressure, demographic change, and housing instability to flag high-risk areas.

**My Personal Contributions**
* **Methodological Framework:** Led the literature review to establish three distinct metric-based definitions of "gentrification risk." This research-driven approach ensured the model accounted for diverse policy lenses, such as housing cost burdens versus demographic shifts.
* **Data Strategy & Sourcing:** Identified and integrated non-traditional data sources, including eviction filings and building permit data, to supplement standard Census metrics, providing a more real-time view of neighborhood change.

---

## Nonprofit Engagements
*Projects where I worked with external stakeholders to deliver real-world impact.*

### Addressing Disproportionate Gun Possession Charges among Young Black Men in Englewood
**Tools:** R (Tidyverse, ggplot2)  
*Client: Teamwork Englewood*

**The Overview** Leading a team of 5, we analyzed Chicago crime data, particularly looking at first-time gun possession cases among young Black men in Englewood. 

---

### Website Redesign
**Tools:** UX Design  
*Client: Connections for Abused Women and their Children*

**The Overview** Leading a team of 10, we modernized a website for a local nonprofit, enhancing accessibility, navigation to vital resources, and donation conversion. 