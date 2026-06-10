# Health-Patterns-in-the-U.S.-An-Analysis-of-Obesity-Physical-Activity-and-Diet-Using-BRFSS-Data
Analysis of BRFSS data on obesity, physical activity, and diet across U.S. states and demographic groups using R.

This project analyzes state-level health behavior and outcome data from the Behavioral Risk Factor Surveillance System (BRFSS). The dataset includes measures of overweight, obesity, physical activity, fruit consumption, and vegetable consumption across U.S. locations and demographic subgroups.

The goal of this project is to explore how these health indicators vary by state, year, age, income, and education, and to identify patterns that may reflect public health disparities.

## Dataset
The dataset used in this project is:

**Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System**

It contains:
- Year
- Location
- Health question and response percentage
- Sample size
- Confidence limits
- Demographic subgroup variables such as age, education, sex, income, and race/ethnicity

## Tools Used
- R
- RStudio
- tidyverse
- janitor
- dplyr
- stringr
- ggplot2
- gt

## Analysis Overview
The analysis includes:
- Data cleaning and standardization
- Creation of shortened question labels
- Summary tables of health indicators
- Top 10 locations for each question
- Bottom 5 locations for low fruit and low vegetable consumption
- Visualizations of obesity trends and subgroup differences
- Regression analysis examining relationships between age and health outcomes

## Key Findings
This analysis highlights differences in health outcomes across states and demographic groups. The results suggest that age, income, and education are important factors associated with obesity and related health behaviors.

## Files in This Repository
- `analysis.Rmd` — R Markdown analysis file
- `Visualizations and outputs/trends`
- `README.md` — project overview
- `Dataset CSV`- Link is here:https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system?from_hint=eyJxIjoiTlVUUklUSU9OLCBQSFlTSUNBTCBBQ1RJVklUWSIsInNvcnQiOiJyZWxldmFuY2UifQ%3D%3D

## How to Reproduce
1. Clone this repository.
2. Open the `.Rmd` file in RStudio.
3. Run the code chunks from top to bottom.
4. Render the document to HTML.

## Author
Komen Kipkoros Meshack
