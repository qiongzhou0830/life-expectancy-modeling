# County-Level Life Expectancy Modeling

This project analyzes county-level life expectancy in the United States using health, socioeconomic, and demographic variables. The goal is to identify important predictors of life expectancy and compare different statistical models for prediction and interpretation.

## Project Overview

The analysis focuses on factors such as food insecurity, adult smoking, physical inactivity, diabetes prevalence, median income, and state-level differences. I used exploratory data analysis, linear regression, model selection, and test-set prediction error to evaluate model performance.

## Methods

* Data cleaning and exploratory data analysis
* Correlation analysis and visualization
* Linear regression modeling
* ANCOVA model with state fixed effects
* Model selection using BIC
* Model comparison using F-test and test-set RMSE
* Residual diagnostics and multicollinearity checks

## Key Findings

* Life expectancy showed strong negative relationships with food insecurity, adult smoking, physical inactivity, and diabetes prevalence.
* Median income was positively associated with life expectancy.
* Although state-level differences existed, the reduced model selected by BIC provided a more concise model with better balance between interpretability and complexity.
* Residual plots and test-set prediction error were used to evaluate model assumptions and predictive performance.

## Files

* `code/life_expectancy_analysis.Rmd`: Reproducible R Markdown analysis file
* `report/life_expectancy_report.pdf`: Final project report
* `figures/`: Main plots and diagnostic figures
* `data/README.md`: Notes about dataset availability

## Tools

R, R Markdown, linear regression, model selection, residual diagnostics, data visualization
