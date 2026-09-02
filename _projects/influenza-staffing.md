---
layout: default
title: Influenza Staffing Forecast
description: Analysis of influenza mortality patterns to forecast where and when medical staffing resources would be most needed.

---

# Influenza Staffing Forecast

**Tools:** Tableau · Excel

**Skills:** Data Cleaning · Data Integration · Data Transformation · Statistical Analysis · Data Visualization · Forecasting · Data Storytelling

## Project Overview

This project analyzed historical influenza mortality data to determine when and where a medical staffing agency should deploy temporary medical staff during influenza season.

Hospitals and clinics experience increased demand during influenza season, particularly when vulnerable populations develop serious complications requiring hospitalization. The staffing agency in this scenario provides temporary nurses, physician assistants, and doctors to help meet that increased demand.

The analysis focused on developing a staffing plan for hospitals across all 50 U.S. states.

## Business Questions

The project focused on three primary questions:

1. **Which age group is most vulnerable to influenza?**
2. **Where is the greatest demand for additional medical staff?**
3. **When does influenza season create the greatest demand for medical staff?**

The ultimate goal was to determine when to send staff and how many staff members to send to each state.

## Data

The analysis combined two datasets covering **2009–2017**.

### U.S. Census Data

The Census dataset contains county- and state-level population data for the United States from 2009–2017.

**[U.S. Census Population Data](https://www.census.gov/programs-surveys/popproj/data/datasets.2017.List_346363885.html#list-tab-List_346363885)**

### CDC Influenza Deaths Data

The CDC dataset contains monthly U.S. influenza death counts from 2009–2017.

**[CDC Influenza Deaths Data](https://wonder.cdc.gov/ucd-icd10.html)**

## Tools & Methods

The project used **Excel** and **Tableau** to clean, integrate, analyze, and visualize the data.

The analysis process included:

- Data cleaning
- Data integration
- Data transformation
- Statistical hypothesis testing
- Visual analysis
- Forecasting
- Tableau data storytelling

The Census and CDC datasets were combined to examine influenza mortality in relation to population size and geographic location.

## Analysis

### Vulnerable Age Groups

The analysis examined influenza deaths across age groups to determine which populations were most vulnerable.

The **65+ age group had the highest number of deaths** in the analysis.

This finding suggests that patients over 65 should receive particular attention when planning medical staffing resources.

### Geographic Demand

The analysis mapped influenza deaths by population to identify states with the greatest potential demand for medical staff.

Among the 65+ population, the three states with the highest influenza death totals were:

1. **California**
2. **New York**
3. **Texas**

These states represent the highest-priority locations identified by the analysis for additional staffing resources.

### Seasonal Demand

The analysis examined influenza deaths by month to identify when demand for medical staff would be greatest.

Influenza deaths tended to peak during the winter months:

- November
- December
- January

This suggests that **November through January** represents the most critical period for medical staffing preparation and deployment.

## Key Findings

### 1. Adults 65+ were the most vulnerable population

The 65+ age group had the highest number of influenza deaths.

### 2. California, New York, and Texas had the highest identified demand

These three states had the highest influenza death totals among the 65+ population.

### 3. Staffing demand is highest during the winter

Influenza deaths tended to peak during November, December, and January.

### 4. Staffing should be planned before peak demand

Because the highest mortality occurred during the winter months, medical staffing resources should be prepared and deployed with the November–January period in mind.

## Recommendations

Based on the analysis, I recommended:

- **Increasing medical staffing in California, New York, and Texas**, the three states with the highest influenza death totals identified in the analysis.
- **Prioritizing patients over age 65** when planning resources because this population experienced the highest number of deaths.
- **Preparing staffing resources for November through January**, when influenza deaths tended to peak.

The project defined success as using available agency staff according to state requirements while minimizing instances of both understaffing and overstaffing.

A state was considered understaffed when the staff-to-patient ratio fell below 90% of the required ratio and overstaffed when it exceeded 110%.

## Data Limitations

The analysis has several important limitations.

The datasets cover **2009–2017**, meaning the totals do not represent current influenza mortality patterns.

Additionally:

- Some values are estimates.
- Some numbers may not add up exactly to reported totals.
- Heavy reliance on survey data may introduce bias from respondents interpreting questions differently.
- The data does not represent a complete count of all influenza visits or laboratory tests in the United States.

These limitations should be considered when applying the findings to current staffing decisions.

## Conclusion

This analysis demonstrated how historical public-health data can be combined with demographic and geographic information to support resource-planning decisions.

The analysis identified **adults 65+ as the most vulnerable population**, **California, New York, and Texas as the states with the highest identified influenza mortality among that population**, and **November through January as the period when influenza deaths tended to peak**.

Together, these findings provide a framework for anticipating where and when additional medical staffing resources may be needed.

## Lessons Learned

This project strengthened my ability to:

- Clean and combine datasets from different sources
- Test data against a hypothesis
- Perform statistical analysis
- Analyze geographic and demographic patterns
- Create visualizations in Tableau
- Present analytical findings through data storytelling
- Consider limitations when interpreting analytical results

## Full Tableau Presentation

**[View the Full Influenza Data Story in Tableau](https://public.tableau.com/views/EX2_9InfluenzaDataStory/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**
