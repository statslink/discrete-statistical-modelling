# Small-Sample Discrete Distribution Analysis

This project presents a statistical analysis of a discrete dataset (n = 100) using classical inference methods and model comparison.

## Overview

The goal is to:
- explore the empirical properties of the sample,
- propose candidate distributions,
- estimate their parameters,
- and evaluate goodness-of-fit.

The following discrete models are considered:
- Poisson
- Binomial
- Geometric (Geom₀)

## Methods

The analysis includes:
- Exploratory Data Analysis (ECDF, boxplot, frequency tables)
- Parameter estimation via:
  - Method of Moments
  - Maximum Likelihood Estimation
- Theoretical validation:
  - Unbiasedness
  - Consistency
  - Efficiency (Cramér–Rao bound)
- Asymptotic confidence intervals (CLT-based)
- Chi-square goodness-of-fit testing

## Results

- The Poisson model is rejected at both α = 0.05 and α = 0.01  
- The geometric model is not rejected and provides a better fit  
- The data exhibits overdispersion, suggesting that more flexible models (e.g. negative binomial) could be explored

## Reproducibility

Install dependencies:

pip install numpy matplotlib seaborn scipy

Then run the notebook or script to reproduce all results.

## Author

Yurii Liudomyrskyi
