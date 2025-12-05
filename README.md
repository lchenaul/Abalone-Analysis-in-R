# Abalone Analysis in R

This project uses ANOVA, regression, and ROC analysis to understand how abalone age, sex/type, and volume relate to shuck weight. The goal is to identify biological patterns and determine sustainable volume cutoffs for harvesting.



## Key Insights
- CLASS (age) strongly affects the shuck-to-volume ratio; older abalones have lower efficiency.
- Log-transforming volume and shuck weight improves linearity and regression assumptions.
- L_VOLUME is the strongest predictor of shuck weight; TYPE is statistically significant but has minor practical impact.
- Harvest cutoffs involve trade-offs:
  - High cutoffs protect infants but reduce yield.
  - Low cutoffs increase yield but risk overharvesting juveniles.
  - ROC analysis identifies an optimal cutoff balancing conservation and harvest size.

## Skills Demonstrated
ANOVA, multiple regression, log transformations, diagnostics, ROC curves, cutoff selection, and reproducible R Markdown workflow.



