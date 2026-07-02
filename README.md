# State-Level Inflation Expectations Analysis Using Google Trends

Independent econometrics project completed in R examining whether Google search behavior can explain differences in inflation expectations across U.S. states.

## Project Overview:
This project examines whether Google search activity related to rent, gas prices, and unemployment can help explain differences in state-level inflation expectations using multiple linear regression.

Using Google Trends search data and the New York Federal Reserve Survey of Consumer Expectations, I constructed state-level measures of inflation expectations and evaluated their relationship with online search activity through multiple linear regression. 

## Research Question:
Can Google search interest in inflation related topics predict state-level inflation expectations?

## Data sources:
* Google Trends
* New York Federal Reserve Survey of Consumer Expectations

## Methods:
* Data cleaning and validation
* Dataset merging
* Weighted calculations
* Multiple linear regression
* Data visualization
* Multicollinearity diagnostics

## Tools Used:
* R
* tidyverse
* fixest
* ggplot2

## Results

The analysis found limited evidence that Google search activity significantly predicts state-level inflation expectations. Although the models did not provide strong predictive power, the project demonstrates the complete workflow of collecting, cleaning, merging, validating, modeling, and interpreting multiple public datasets in R.

## Repository Contents

- README.md – Project overview and methodology
- inflation_analysis.Rmd – Complete R Markdown analysis
- inflation_analysis.html – Rendered project report
- data/ – Cleaned datasets used in the analysis
