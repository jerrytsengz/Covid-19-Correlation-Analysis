# COVID-19 Symptom Correlation Analysis

## About

This project presents an analysis of COVID-19 data to identify correlations between symptom status, age, and gender. The analysis leverages data visualization techniques to draw meaningful insights from the data.

## Goal

The primary goal of this analysis is to determine if there is any correlation between symptom status (symptomatic or asymptomatic) and demographic factors such as age and gender.

## Insights

- **Symptomatic cases** are more common in females than males, with a significant difference observed in the 18-49 year age group.
- **Asymptomatic cases** are fairly distributed across genders and age groups.
- Individuals aged **18-49** are more likely to contract COVID-19, potentially due to the larger size of this age group in the population.

## Data

The data used in this analysis spans from January 2020 to December 2021 and includes:
- Symptom status (symptomatic or asymptomatic)
- Gender (female or male)
- Age groups (0-17, 18-49, 50-64, 65+)

Key figures include:
- Total symptomatic cases: 227,680
- Total asymptomatic cases: 7,700
- Gender distribution: 123,432 females and 111,948 males
- Age group distribution: 40,323 (0-17), 128,297 (18-49), 39,056 (50-64), 27,704 (65+)

## Process

1. **Data Wrangling**: Filtering the data to include only relevant columns (sex, age_group, symptom_status) and removing unknown or missing values.
2. **Visualization**: Using Python libraries like Seaborn and Matplotlib to create tables and pie charts that illustrate the distribution of symptom status by age and gender.

## Recommendation Report

For a detailed exploration of the data, findings, and visualizations, please refer to the [Covid-19-Findings.pdf](./Covid-19-Findings.pdf).

