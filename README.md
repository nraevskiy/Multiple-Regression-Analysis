# Multiple Regression Analysis

This repository contains coursework and analysis from the *Business Insights through Data (DAT-3533)* MBA course. The focus of this project is on applying **multiple linear regression models** to real business scenarios and interpreting outputs using Excel.

## Objectives

- Use of **multiple independent variables** to predict outcomes
- Incorporate **dummy variables** and **interaction terms**
- Evaluate model performance using **R², adjusted R²**, and **significance tests**
- Demonstrate ability to translate quantitative analysis into business insights

## Data

The data is from a course assignment and involves running regression models to analyze relationships between dependent and independent variables. Categorical variables were encoded using dummy variables.

- `data/Multiple_Regression_assignment_answer_keys.xlsx`

## Key Concepts

Based on lecture materials:

- Dummy Variable Regression (Page 3–5)  
- Interpreting Coefficients (Page 5)  
- Interaction Effects in Regression (Page 9–11)  
- Model Evaluation using F-test and Significance (Page 12)  

Reference: `slides/Class_7_optional_slides.pdf`:contentReference[oaicite:0]{index=0}

## File Overview

| Folder | Content |
|--------|---------|
| `data/` | Excel file with regression results |
| `slides/` | Lecture material used as reference |
| `analysis/summary.md` | Summary of key learnings, variable significance, and model insights |

## Sample Regression Equation

```text
Y = β₀ + β₁X₁ + β₂X₂ + β₃X₁X₂ + ε
