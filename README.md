## Global Health in Numbers: A Statistical Dive into Life Expectancy (2000–2015)

### Overview

This project provides a comprehensive statistical analysis of global life expectancy trends from 2000 to 2015. Using a curated dataset of 2,865 observations across 179 countries, the analysis explores key health, socioeconomic, and demographic indicators that influence life expectancy.

The aim is to identify disparities in longevity, understand contributing factors, and provide insights that can guide policymakers, health organizations, and NGOs in improving global health outcomes.

### Dataset

Source: Kaggle – Life Expectancy WHO Updated Dataset

Period: 2000–2015

Observations: 2,865

Features (21): Includes variables such as Infant Deaths, Adult Mortality, Alcohol Consumption, GDP per Capita, Immunization Coverage (Polio, Diphtheria, Hepatitis B, Measles), Schooling, and Life Expectancy (target variable).

### Objective

Key questions addressed in this analysis:

What is the global distribution of life expectancy?

What factors most strongly influence life expectancy across countries?

How do education and immunization programs impact average lifespan?

### Methodology

Data Exploration & Cleaning:

Checked for missing values and handled inconsistencies.

Focused on Life_expectancy as the primary variable.

### Exploratory Data Analysis (EDA):

Visualizations: Histogram, Boxplot, Scatterplots, Regression plots.

Numerical Summaries: Mean, Median, Mode, Variance, Standard Deviation, Interquartile Range, Trimmed Means.

Sampling & Confidence Intervals:

Random 10% sample to validate representativeness.

Computed 75%, 85%, and 95% confidence intervals for the population mean.

### Hypothesis Testing:

Two-tailed Z-test to evaluate if global life expectancy differs from an assumed benchmark (70 years).

### Correlation Analysis:

Investigated relationships between life expectancy and variables such as Adult Mortality, Schooling, Immunization Coverage (Polio & Diphtheria).

Calculated correlation coefficients and coefficient of determination (R²) to quantify relationships.

### Key Findings

Global Life Expectancy:

Mean: 68.86 years

Median: 71.40 years

Mode: 72.60 years

Range: 44.4 years, indicating significant disparities across countries.

### Confidence Intervals:

75% CI: (68.65, 69.06)

85% CI: (68.60, 69.11)

95% CI: (68.51, 69.20)

### Hypothesis Testing:

Sample mean: 69.17 years

Z-test: Failed to reject null hypothesis (p-value: 0.1365), suggesting the mean is not significantly different from 70 years at 5% significance.

Correlation Insights:

Positive Predictors: Schooling (r = 0.7325), Polio Vaccination (r = 0.6412), Diphtheria Immunization (r = 0.6275)

Negative Predictors: Adult Mortality (r = -0.9454), Infant Deaths (r = -0.9200)

These results highlight the importance of healthcare, immunization programs, and education in increasing life expectancy.

### Visualizations

Histograms and boxplots of life expectancy to identify distribution and outliers.

Regression plots for:

Polio vaccination vs Life Expectancy

Adult Mortality vs Life Expectancy

Diphtheria Immunization vs Life Expectancy

Average Schooling vs Life Expectancy

These plots reinforce the statistical findings and make patterns easily interpretable.

### Tools & Libraries

Python 3.12

Libraries:

pandas – data manipulation

numpy – numerical computations

matplotlib & seaborn – data visualization

scipy.stats – statistical analysis


### Conclusion

This analysis demonstrates the global disparities in life expectancy and identifies key positive and negative factors influencing longevity. Policies targeting education, vaccination programs, and adult health interventions are likely to have a measurable impact on life expectancy.

This report serves as a data-driven resource for global health organizations, policymakers, and NGOs to make informed decisions and plan effective interventions.

### References

World Health Organization. Global Health Observatory Data. Link

United Nations Data. Link

Kaggle. Life Expectancy WHO Updated Dataset. Link

Pandas Documentation: https://pandas.pydata.org

Seaborn Documentation: https://seaborn.pydata.org

Matplotlib Documentation: https://matplotlib.org
