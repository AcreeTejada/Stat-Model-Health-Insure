# Statistical-Modeling-Health-Insurance
Exploring Health Insurance Costs & Factors

This project uses statistical modeling techniques in R to analyze how region and the number of children effect to health insurance costs using the Kaggle Insurance dataset.

Methods used are as follows:
- Linear regression
- Transformation (log)
- Interaction terms
- Quadratic terms
- Model diagnostics (residuals, QQ plots, constant variance checks)
- R, tidyverse

Key Findings:
- The region slightly explains the variation in insurance cost
- The number of children has a positive but weak relationship
- Adding a quadratic term improved the fit and addressed nonlinearity
- Model assumptions remained partially violated (heteroscedasticity)

Files included:
- PDF report
- QMD source

Dataset: Kaggle (Insurance Dataset)

Future Work:
A potential next step is to use the quadratic formula to estimate the peak effect of children on insurance cost rather than relying only on confidence intervals; this will provide a more accurate interpretation of the turning point in the quadratic model. Next could be to include demographic predictors like age, BMI, smoking status to increase explanatory power, and address the remaining heteroscedasticity through alternative transformations, possibly weighted least squares.
