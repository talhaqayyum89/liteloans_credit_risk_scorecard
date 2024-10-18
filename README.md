# Lite Loans Scorecard Development Plan

## Introduction
The Lite Loans Scorecard Development Plan aims to build a robust credit scoring model to enhance the customer onboarding process through an application-to-through-the-cycle strategy. This solution is designed to meet critical business requirements: reliability, transparency, and a profit and growth-driven focus.

### Business Goal
The primary objective is to develop a credit scoring model that supports automation and optimization of the customer onboarding process.

### Project Goal
The Lite Loan credit risk application scorecard will assist in evaluating the probability of customer defaults. This end-to-end advanced credit risk analytics process focuses on:
- Meeting business goals
- Optimizing the overall customer acquisition funnel by leveraging insights from the scoring model within GDS (and/or Provenir)
- Building a holistic customer risk profile for Lite-loan customers

## Project Overview

### PART 1: Data Preparation and Exploratory Data Analysis
- **Operational Risk IDs Removal:** Ensure the dataset is clean by removing any operational risk identifiers.
- **Data Audit:** Conduct thorough verification of data quality.
- **Distribution Analysis:**
  - Analyze the distribution of Through-the-door Applications (Feb - Aug 2021) to understand take-up rates.
  - Examine trends in application loan ticket size distribution.
  - Assess the distribution of Through-the-door Loan Applications by channel.
  - Analyze the trend of total application population versus acceptance and decline rates month-on-month.
  - Identify the top reasons for lite loan application rejections.
  - Review month-on-month trends in disbursed loan ticket sizes.

### PART 2: Behavioral Analysis
- Analyze early settlement events across disbursed samples (Feb - Dec 2021).
- Exclude early **settlement flag 1** from the disbursed population.
- Understand maximum delinquency event trends for Lite loans, including:
  - Default rates analysis
  - Cure rates analysis
- Define target definitions:
  - Good/Bad flag

### PART 3: Feature Engineering
- Develop cross variables and ratios to enhance the dataset.

### PART 4: Data Preparation
- Generate a Characteristics Analysis Report, including:
  - Fine Classing
  - Coarse Classing
  - Information Value analysis
  - Weight of Evidence (WoE) transformations
  - Univariate Analysis and Feature Selection

### PART 5: Scorecard Development
- **Modeling Phase:**
  - Conduct variable selection for the scoring model.
  - Perform model correlation analysis.
- **Model Evaluation:**
  - Validate using Hold-Out Sample.
  - Conduct Out-of-Time validation.
  - Perform Recent Sample validation.
  - Validate score performance.
  - Conduct score calibration.

### PART 6: Cut-off Strategy
- Perform cut-off analysis and swap-set analysis.
- Conduct profitability analysis, including cost analysis with dependencies (unit economics):
  - Customer acquisition costs
  - Marketing costs
  - Overheads & variable costs
- Analyze the distribution of the Probability of Defaults (PDs).

## Conclusion
The Lite Loans Scorecard Development Plan integrates advanced analytics and modeling techniques to enhance the credit risk assessment process, ultimately driving efficiency in customer onboarding and improving decision-making in the lending process.
