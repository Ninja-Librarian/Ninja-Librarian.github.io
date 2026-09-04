---
layout: default
title: UFC Fight Analysis
description: Python analysis of UFC fight statistics using correlation analysis, linear regression, clustering, and time-series techniques to explore factors associated with fighter performance.
order: 5
---

**Tools:** Python · Excel · Tableau

**Skills:** Data Cleaning · Exploratory Data Analysis · Correlation Analysis · Linear Regression · K-Means Clustering · Time-Series Analysis · Data Visualization

## Project Overview

This project analyzed UFC fight statistics to explore the factors associated with fighter performance and a greater chance of victory.

The analysis combined fighter physical attributes, career statistics, fight performance statistics, and fight outcomes to identify relationships and patterns within UFC data.

The project also applied several statistical and machine learning techniques to examine relationships between variables and identify patterns across weight classes and time.

## Business Questions

The analysis focused on questions such as:

1. What fighter attributes and career statistics are associated with successful performance?
2. What relationships exist between physical attributes such as height, weight, and reach?
3. Can fighters be grouped into meaningful clusters based on physical characteristics?
4. What patterns can be identified in significant striking performance over time?

## Data

The dataset included several categories of UFC information:

- Fighter corner designation (Red or Blue)
- Physical attributes
- Fight performance statistics
- Fighter career statistics
- Fight winners
- Win conditions

The data contained information about both individual fighters and their fight histories.

## Tools & Methods

Python was used for exploratory analysis, statistical testing, machine learning, and visualization.

The analysis included:

- Correlation matrix heatmaps
- Linear regression
- K-means clustering
- Dickey-Fuller testing
- Autocorrelation analysis
- Data visualization

Excel and Tableau were also used during the project to support data analysis and presentation.

## Analysis

### Correlation Analysis

The exploratory analysis began with correlation heatmaps to identify relationships among career statistics and physical attributes.

Career statistics showed strong positive correlations between wins and longest win streak.

Current win streak and longest win streak also showed a strong positive relationship.

Some variables showed little or no correlation with one another. For example, total time fought did not show a meaningful relationship with wins, while current win streak and losses did not show a strong relationship.

Physical attributes also revealed several relationships.

Height and weight were strongly positively correlated, as were reach and weight. Age did not show a meaningful correlation with the physical attributes examined.

These results helped identify which variables warranted additional analysis.

### Linear Regression

Linear regression was used to examine the relationship between fighter height and reach.

The analysis showed a positive relationship between the two variables.

The regression model produced an R² score of approximately **0.74**, indicating that height explained a substantial portion of the variation in reach within the analyzed data.

This supported the finding that reach generally increases as fighter height increases.

### K-Means Clustering

K-means clustering was used to group fighters based on physical characteristics.

The analysis examined height, weight, and reach to identify distinct groupings.

The resulting clusters generally corresponded with different physical profiles and weight classes.

The analysis also showed that reach scales proportionally with height across the identified groupings.

This provided another way to examine fighter characteristics beyond simple correlations.

### Time-Series Analysis

A Dickey-Fuller test was applied to the average significant-strike percentage over time for the lightweight division.

Individual fighters did not have enough observations to perform the analysis independently, so the division's average significant-strike percentage was used instead.

The analysis showed a decline in significant-strike percentage between approximately 2008 and 2012, followed by an increase afterward.

The decomposition also showed a relatively consistent seasonal pattern.

The observed decline may indicate a change in fighting styles during that period, although additional analysis would be necessary to determine the cause.

## Key Findings

The analysis identified several important relationships:

- Wins and longest win streak showed a strong positive correlation.
- Current win streak and longest win streak were strongly correlated.
- Height and weight showed a strong positive relationship.
- Reach and weight showed a strong positive relationship.
- Age did not show a meaningful correlation with the physical attributes examined.
- Linear regression found a positive relationship between height and reach, with an R² of approximately 0.74.
- K-means clustering identified groups of fighters with similar physical characteristics.
- Reach generally increased with height across the identified clusters.
- Lightweight significant-strike percentage declined between approximately 2008 and 2012 before increasing again.
- The time-series analysis showed a relatively consistent seasonal pattern.

## Conclusions

The analysis demonstrates that fighter performance can be examined from several different perspectives, including career statistics, physical attributes, clustering, and changes over time.

The strongest relationships identified in the project involved fighter physical characteristics and career performance measures.

However, the analysis does not establish that any single physical characteristic guarantees victory. Instead, it provides evidence of relationships that could be investigated further with additional fight-level and fighter-level analysis.

## Next Steps

Several opportunities were identified for additional analysis:

- Examine whether fighters in different height ranges tend to prefer particular fighting stances.
- Compare standing strikes and ground strikes across different weight classes.
- Investigate additional relationships with longest win streak, including stance and reach.
- Further examine how physical characteristics relate to fight outcomes.

## Data Limitations

The analysis had several limitations:

- The dataset contained missing values.
- The data was scraped from the UFC website, so details about the original data collection process were unavailable.
- Collection errors may have affected the accuracy of some data.
- UFC rules may have changed over time, which could affect the consistency of how certain statistics were recorded.

These limitations should be considered when interpreting historical comparisons and relationships in the dataset.

## Lessons Learned

This project expanded my experience with Python-based statistical and machine learning analysis.

In particular, I gained experience with:

- Linear regression
- K-means clustering
- Dickey-Fuller testing
- Autocorrelation analysis
- Correlation analysis
- Exploratory data analysis

The project also demonstrated the importance of selecting analytical techniques based on the type of question being investigated and the structure of the available data.

## Project Resources

The complete analysis is available in my GitHub repository.

The project visualizations and presentation are also available through my Tableau portfolio.
