# Data-Driven Pay Equity Analysis Using Statistical & Predictive Models

## Overview
This project analyzes workforce compensation data to examine pay equity across gender while accounting for job role, department, education level, experience, age, and performance. The goal is to identify whether observed pay gaps persist after controlling for structural and individual-level factors, and to uncover the true drivers of compensation.

## Problem Statement
Gender-based pay disparities are frequently reported, but raw salary comparisons can be misleading due to confounding factors such as job role and seniority. This project investigates whether pay gaps exist beyond these factors and evaluates which variables most strongly influence compensation outcomes.

## Dataset
The dataset was collected from Glassdoor and includes the following attributes:
- Job Title  
- Gender  
- Age  
- Department  
- Education Level  
- Seniority  
- Performance Evaluation  
- Base Pay  
- Bonus  

The data spans multiple roles including technical, managerial, and operational positions, providing a broad representation of workforce compensation.

## Methodology
The analysis combines statistical testing and predictive modeling techniques:
- Independent t-tests and ANOVA to assess raw salary differences
- Non-parametric tests when statistical assumptions were violated
- Multiple linear regression to model salary determinants
- Logistic regression to analyze likelihood of being a top 10% earner
- Diagnostic checks for normality, homoscedasticity, and multicollinearity

## Key Findings
- A raw gender pay gap exists but largely disappears after controlling for job role and department
- Job title, seniority, and age are the strongest predictors of salary
- Education increases compensation but does not significantly reduce gender-based differences
- Performance evaluations have limited impact on pay outcomes
- Structural factors dominate compensation outcomes over demographic variables

## Impact
This project demonstrates how data-driven analysis can move beyond surface-level conclusions and provide actionable insights for HR teams, leadership, and policy stakeholders to support fair and transparent compensation practices.

## Tools & Technologies
- Statistical Analysis
- Regression Modeling
- Hypothesis Testing
- Predictive Modeling
- Data Analysis

## Future Work
- Incorporate promotion history and career progression data
- Expand dataset across multiple organizations and time periods
- Apply causal inference techniques to isolate gender-related effects
- Analyze salary growth trends instead of static compensation levels
