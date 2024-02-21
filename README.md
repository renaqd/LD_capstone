# Capstone Project
#### IBM Data Science Certificate
#### Lorena Dorado

## Executive Summary
For a competitive edge, team Space Y proposes the development of a new rocket that will cost less than Falcon 9.
1. Methodology
2. Insights from EDA
3. Proximities Analysis
4. Dashboard with Plotly Dash
5. Predictive Analysis

## Introduction
The SpaceX Falcon 9 launch vehicle represents an important milestone in the modern age due to its reusability.  In the past, all rockets were built for single-use as they would fall out of the atmosphere as soon as the fuel ran out.  The Falcon 9's first stage is capable of landing itself upright and its reusability significantly reduces the cost of launching vehicles into orbit. The goal of this analysis is to find all the data regarding what makes a quality rocket. It is important to study the success and failure rates of SpaceX for technological advancement.


## Methodology
1. Data collection methodology:
    Collect most recent Falcon 9 data from the Space X API 
2. Perform data wrangling:
    Clean the data to determine variables affecting rocket landing outcome by studying launch site and success rates
3. Perform exploratory data analysis (EDA) using visualization and SQL
4. Perform interactive visual analytics using Folium and Plotly Dash
5. Perform predictive analysis using classification models


## EDA with Data Visualization
Used the following plots to determine relationship and patterns between different parameters:
  Flight Number vs. Payload Mass – visualize first stage success based on mass
  Flight Number vs. Launch Site – identify geographical factors
  Payload Mass vs. Launch Site – support study
  Success Rate vs. Orbit Type – identify any trends in destination
  Orbit Type vs. Flight Number and Orbit Type vs. Payload mass
  Success Rate vs. Year – to monitor improvements
EDA with SQL
  statements to calculate and explore the data


## Build an Interactive Map with Folium
  Marker objects – Indicate Success(green) /Fail(red) counts per launch site.
  Circles – highlight general area and examine landscape
  Lines – boundaries to further examine geographical advantages/disadvantages and distance


## Build a Dashboard with Plotly Dash
  Interactive dashboard showing individual site statistics success and failure rates.
  Scatter Plot with Range Slider – shows frequency and Booster Version handling the Payload Mass


## Predictive Analysis (Classification)
  Classify columns, standardize the data, train the data
  Goal: Find important features and determine the best performing method for accuracy


## Results: Data Visualization
  1. Flight Number vs. Launch Site
  2. Payload vs. Launch Site
  3. Success Rate vs. Orbit Type
  4. Flight Number vs. Orbit Type
  5. Payload vs. Orbit Type
  6. Launch Success Yearly Trend


## Results: Dashboard
1. Launch Records
2. Launch Success Ratio
3. Payload range (Kg) Slider


## Results: Modeling
1. Classification
2. Confusion Matrix


## Discussion
Success rates vary per launch site
Correlation detected between Payload and first stage return
Best method performers: KNN, SVM, and Logistic Regression
