---
layout: default
title: UFC Fight Analysis
description: Python analysis of UFC fight statistics using correlation analysis, linear regression, clustering, and time-series techniques to explore factors associated with fighter performance.
order: 5
--------

**Tools:** Python · Excel · Tableau

**Skills:** Data Cleaning · Exploratory Data Analysis · Correlation Analysis · Linear Regression · K-Means Clustering · Time-Series Analysis · Data Visualization

## Project Overview

This project analyzed UFC fight statistics to explore factors associated with fighter performance and a greater chance of victory.

The analysis combined fighter physical attributes, career statistics, fight performance statistics, and fight outcomes to identify relationships and patterns within UFC data.

Several statistical and machine learning techniques were applied to examine relationships between variables, group fighters based on physical characteristics, and identify changes in fight performance over time.

## Business Questions

The analysis focused on several questions:

1. What fighter attributes and career statistics are associated with successful performance?
2. What relationships exist between physical attributes such as height, weight, and reach?
3. Can fighters be grouped into meaningful clusters based on physical characteristics?
4. What patterns can be identified in significant striking performance over time?

## Data

The dataset included several categories of UFC information:

* Fighter corner designation (Red or Blue)
* Physical attributes
* Fight performance statistics
* Fighter career statistics
* Fight winners
* Win conditions

The data contained information about individual fighters and their fight histories.

## Tools & Methods

Python was used for exploratory analysis, statistical analysis, machine learning, and visualization.

The analysis included:

* Correlation matrix heatmaps
* Linear regression
* K-means clustering
* Dickey-Fuller testing
* Autocorrelation analysis
* Time-series decomposition
* Data visualization

Excel and Tableau were also used to support data analysis and presentation.

## Analysis

### Correlation Analysis

The exploratory analysis began with correlation heatmaps to identify relationships among career statistics and physical attributes.

Career statistics showed a strong positive correlation between **wins and longest win streak**.

**Current win streak and longest win streak** also showed a strong positive relationship.

Other variables showed little or no meaningful correlation. For example, total time fought did not show a meaningful relationship with wins, while current win streak and losses did not show a strong relationship.

Physical attributes revealed several additional relationships.

**Height and weight** were strongly positively correlated, as were **reach and weight**. Age did not show a meaningful correlation with the physical attributes examined.

These results helped identify variables for further analysis.

### Linear Regression

Linear regression was used to examine the relationship between **fighter height and reach**.

The analysis showed a positive relationship between the two variables.

The regression model produced an **R² of approximately 0.74**, indicating that height explained a substantial portion of the variation in reach within the analyzed data.

This supported the finding that reach generally increases as fighter height increases.

### K-Means Clustering

K-means clustering was used to group fighters based on physical characteristics.

The analysis examined **height, weight, and reach** to identify distinct groupings.

The resulting clusters generally corresponded with different physical profiles and weight classes.

The analysis also showed that reach scaled proportionally with height across the identified groupings.

Clustering provided another way to examine fighter characteristics beyond individual correlations.

### Time-Series Analysis

A Dickey-Fuller test was applied to the **average significant-strike percentage over time for the lightweight division**.

Individual fighters did not have enough observations to perform the analysis independently, so the division's average significant-strike percentage was used instead.

The analysis showed a decline in significant-strike percentage between approximately **2008 and 2012**, followed by an increase afterward.

Time-series decomposition also showed a relatively consistent seasonal pattern.

The observed decline may indicate a change in fighting styles during that period, although additional analysis would be necessary to determine the cause.

## Key Findings

The analysis identified several important relationships and patterns:

* Wins and longest win streak showed a strong positive correlation.
* Current win streak and longest win streak were strongly correlated.
* Height and weight showed a strong positive relationship.
* Reach and weight showed a strong positive relationship.
* Age did not show a meaningful correlation with the physical attributes examined.
* Linear regression found a positive relationship between height and reach, with an R² of approximately 0.74.
* K-means clustering identified groups of fighters with similar physical characteristics.
* Reach generally increased with height across the identified clusters.
* Lightweight significant-strike percentage declined between approximately 2008 and 2012 before increasing again.
* The time-series analysis showed a relatively consistent seasonal pattern.

## Conclusions

The analysis demonstrates how fighter performance can be examined from several different perspectives, including career statistics, physical attributes, clustering, and changes over time.

The strongest relationships identified in the project involved **fighter physical characteristics and career performance measures**.

However, the analysis does not establish that any single physical characteristic guarantees victory. Instead, it identifies relationships that could be investigated further through additional fight-level and fighter-level analysis.

## Next Steps

The analysis identified several opportunities for additional investigation:

* Examine whether fighters in different height ranges tend to prefer particular fighting stances.
* Compare standing strikes and ground strikes across different weight classes.
* Investigate additional relationships with longest win streak, including stance and reach.
* Further examine how physical characteristics relate to fight outcomes.

These analyses could help determine whether the relationships identified in the exploratory analysis remain meaningful when additional fighter and fight characteristics are considered.

## Data Limitations

The analysis had several limitations:

* The dataset contained missing values.
* The data was scraped from the UFC website, so details about the original data collection process were unavailable.
* Collection errors may have affected the accuracy of some data.
* UFC rules may have changed over time, which could affect the consistency of how certain statistics were recorded.
* Individual fighters did not have enough observations for the lightweight time-series analysis, requiring the use of division-level averages instead.

These limitations should be considered when interpreting historical comparisons and relationships in the dataset.

## Lessons Learned

This project expanded my experience with Python-based statistical and machine learning analysis.

In particular, I gained experience with:

* Correlation analysis
* Linear regression
* K-means clustering
* Dickey-Fuller testing
* Autocorrelation analysis
* Time-series analysis
* Exploratory data analysis

The project also reinforced the importance of selecting analytical techniques based on the type of question being investigated and the structure of the available data.

Using several analytical approaches also demonstrated how different techniques can provide complementary perspectives on the same dataset.

## Project Resources

[The complete analysis is available in my GitHub repository](https://github.com/Ninja-Librarian/UFC-data-analysis).

[View the UFC Fight Analysis Presentation on Tableau](https://public.tableau.com/app/profile/evan.greenwood/viz/EX6_7/EX6_7Presentation)
