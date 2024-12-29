# MLB-Expansion-City

### Task Description
Imagine you are the Commissioner of Major League Baseball (MLB). Your task is to identify a new city within the continental United States that offers the best opportunity to launch a profitable and stable MLB franchise. The goal is to use data-driven insights to recommend the optimal city for expansion.

## MLB Expansion Analysis: City Selection Project
### Overview

This project addresses the challenge of identifying the most profitable and stable city in the continental United States for a new Major League Baseball (MLB) franchise. Using a data-driven approach, I evaluated potential cities based on demographics, economic potential, and the existing sports ecosystem to make an informed recommendation for expansion.

The dataset used in this project was curated by me from various publicly available sources. I independently decided on the analytical approach and methodology to tackle this task, ensuring it was grounded in both data reliability and practical relevance.

### Objectives
City Selection: Identify the best market for MLB expansion based on key metrics.

### Data Insights:
Evaluate population, income levels, and market saturation.

Analyze the impact of minor league presence and professional sports culture.

Revenue Prediction: Estimate potential MLB revenue for candidate cities and rank them based on profitability and sustainability.

### Data Sources and Curation
The dataset was compiled from multiple public sources, including:

US Census Data: For city and metropolitan population and income metrics.

Forbes MLB Valuations: For revenue patterns and market insights.

Sports Market Data: Information on professional and minor league sports teams in candidate cities.

I curated and integrated these datasets to create a comprehensive data foundation for the analysis. The cleaning process involved handling missing values, removing outliers, and ensuring consistency across data points.

### Methodology and Independent Approach
After being tasked with identifying a suitable city for MLB expansion without a predefined methodology, I developed the following approach:

### 1. Data Cleaning and Preparation

Outlier Detection: Identified and removed extreme values in population and income metrics to ensure dataset reliability.

Imputation: Addressed missing data for minor league presence and other features using median imputation and statistical techniques.

Feature Engineering: Created new metrics, such as total_Pro_league, to quantify professional sports saturation.

### 2. Model Training and Calibration

Regression Model:

Trained on curated data to predict MLB revenue using factors such as population, income, and sports market saturation.

Analyzed standardized and unstandardized coefficients to determine feature importance:

Population: Strongest revenue driver.

Minor League Presence: AAA-level teams significantly influence revenue.

Market Saturation: Highlighted competition from other sports leagues (e.g., NHL, MLS).

Evaluation Metrics: Assessed model performance using R-squared, p-values, and RMSE.

### 3. Revenue Prediction
Predicted MLB revenue for 385 candidate cities and ranked them based on revenue potential, population, and economic factors.

Balanced larger markets (e.g., Nashville) with smaller but affluent cities (e.g., Frisco and Sugar Land).

### 4. Visualization and Reporting
Created a PowerPoint presentation showcasing:

Data insights and feature importance.

### Revenue predictions and city rankings.

## Final recommendations for MLB expansion.
### Results
Population as a Driver: Larger cities with higher populations (e.g., New York) consistently generate higher revenues.

High-Income Small Markets: Cities like Sugar Land and Frisco demonstrate strong revenue potential due to high spending power.

Minor League Presence: AAA teams contribute significantly to market stability and fan engagement.

### Recommended Cities

Nashville: Moderate population with strong growth potential and minimal saturation.

Columbus: A promising untapped sports market with balanced population and income levels.

Frisco: High median income compensates for its smaller population base.

### Tools and References
Tools Used: Python (for data curation, cleaning, and modeling), Excel, and PowerPoint.

### References:
US Census Data

Forbes MLB Valuations

Additional public datasets on sports and economic metrics.
