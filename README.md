
# Consumer Behavior Towards Organic Food: Cognitive-Affective Mediation, Certification Trust, Price Barriers, and Demographic Drivers

## Overview

This project investigates the psychological and socioeconomic factors influencing organic food purchasing decisions, using survey data from Poland and Zimbabwe. The analysis tests four major hypotheses:

1. **Theory of Cognitive-Affective Mediation**: Cognitive beliefs about organic food (e.g., health, environment) positively impact affective emotions, which in turn increase purchase frequency.
2. **Certification Trust Chain**: Familiarity with organic certification logos increases purchase frequency and post-purchase confidence.
3. **Moderating Hypothesis of Price Barriers**: The positive effect of affective emotions on purchase intentions is weakened by price perceptions, especially among lower-income consumers.
4. **Country-Specific Demographic Drivers**: Socioeconomic position (SEP) influences cognitive beliefs and purchase frequency differently in Poland and Zimbabwe—directly in Zimbabwe, indirectly via education and urban residency in Poland.

## Data & Methods

- **Survey**: Bilingual (English/Polish) responses, 100 participants per country, balanced sample.
- **Variables**: Cognitive beliefs, affective emotions, purchase frequency/intention, certification familiarity/importance, price perception, SEP (household economics, education, employment).
- **Analysis**: Structural Equation Modeling (SEM), mediation and moderation tests, robust OLS, Johnson-Neyman intervals, multi-group comparisons.

## Key Findings

- **Cognitive-Affective Mediation**: Cognitive beliefs strongly drive affective emotions, which significantly increase purchase frequency. Mediation confirmed via bootstrapped and SEM models.
- **Certification Trust Chain**: Familiarity with certification logos (EU for Poland, ZW for Zimbabwe) boosts purchase frequency and post-purchase confidence. Mediation and SEM support the trust chain.
- **Price Barriers**: High price perception moderates (weakens) the affective → intention link, especially for lower-SES groups. Johnson-Neyman analysis identifies significant moderation regions.
- **Demographic Drivers**: SEP impacts purchase behavior differently by country. In Zimbabwe, SEP directly affects cognition and purchase. In Poland, SEP operates indirectly via education and urban residency. Multi-group SEM and Chow tests confirm structural differences.

## Reproducibility

- All code and data cleaning steps are documented in `final_analysis.qmd`.
- R packages used: tidyverse, lavaan, mediation, psych, modelsummary, interactions, etc.
- Figures and tables are generated for each hypothesis and exported for publication.

## Citation

If you use this project or its findings, please cite the analysis and acknowledge the original survey design.

---
For detailed methods, code, and results, see `final_analysis.qmd` and the output directory.