# Barriers to Mental Health Treatment Access — NSDUH 2023

## Project Overview

This collaborative academic project examined mental health treatment access and psychological distress among U.S. adults using the 2023 National Survey on Drug Use and Health (NSDUH).

The analysis investigated relationships between health insurance, demographics, income, psychological distress, and mental health treatment utilization.

## Tools and Technologies

- SAS Statistical Software
- SAS DATA Step and data preparation
- PROC TTEST
- PROC CORR
- PROC SURVEYLOGISTIC
- Hypothesis Testing
- Correlation Analysis
- Logistic Regression
- Statistical Interpretation

## Dataset

**Source:** 2023 National Survey on Drug Use and Health (NSDUH)

https://www.samhsa.gov/data/data-we-collect/nsduh-national-survey-drug-use-and-health/datafiles

The NSDUH provides nationally representative survey data on substance use, mental health, and treatment access among the U.S. civilian, noninstitutionalized population aged 12 or older.

The project focused on adults, including respondents with a past-year major depressive episode (MDE).

## My Contributions

My assigned responsibilities within the collaborative project were:

1. Hypothesis testing of psychological distress scores.
2. Correlation analysis involving income, psychological distress, and depression indicators.
3. Logistic regression modeling of mental health treatment utilization.
4. Interpretation of findings and development of project conclusions.

Other team members contributed additional descriptive analyses, chi-square testing, normality testing, t-tests, and regression analyses.

## Statistical Analysis

### Hypothesis Testing

Tested whether the mean past-year K6 psychological distress score among adults with a past-year major depressive episode exceeded 14.

- Mean K6 score: approximately 17.37
- Test statistic: t = 43.92
- Statistical significance: p < 0.0001

The analysis found a statistically significant mean score above the hypothesized benchmark.

### Correlation Analysis

Examined relationships among family income, K6 psychological distress scores, and past-year major depressive episode status.

- Income and psychological distress: r = -0.172
- K6 score and MDE indicator: r = -0.504
- Reported statistical significance: p < 0.0001

The negative correlation between income and psychological distress suggests that lower income was associated with higher distress scores.

### Logistic Regression

Used SAS PROC SURVEYLOGISTIC to analyze associations between mental health treatment utilization and demographic and socioeconomic characteristics.

Predictors included:
- Sex
- Age category
- Health insurance status
- Family income

The analysis accounted for survey weights, strata, and clustering.

Key findings:
- Female respondents had higher estimated odds of receiving treatment than male respondents.
- Older age groups showed higher treatment odds relative to ages 18–25.
- Health insurance coverage was associated with higher treatment odds.
- Model concordance statistic: c = 0.619.

The findings describe statistical associations and should not be interpreted as causal effects.

## Key Findings

| Measure | Result |
|---|---|
| Mean K6 score in hypothesis-test subgroup | 17.37 |
| Hypothesis test | p < 0.0001 |
| Income–distress correlation | -0.172 |
| Insurance–treatment association (unadjusted relative risk, group analysis) | 1.41 |
| Logistic regression concordance statistic | 0.619 |

## Project Deliverable

- NSDUH_2023_Mental_Health_Analysis.pptx — Academic project presentation containing SAS code excerpts, statistical outputs, visualizations, and interpretations.

## Limitations

- Results are observational and do not establish causation.
- Survey design and subgroup restrictions affect interpretation.
- The logistic regression model has limited discrimination (c = 0.619).
- This repository documents a collaborative academic analysis; the original complete SAS analysis program is not included.

## Skills Demonstrated

- SAS Programming
- Healthcare and Public Health Analytics
- Hypothesis Testing
- Correlation Analysis
- Logistic Regression
- Complex Survey Data Analysis
- Statistical Interpretation
- Research Reporting

## Project Attribution

This was a collaborative academic project. The sections under 'My Contributions' describe my assigned work, while the presentation documents the broader team's analysis.
