<p align="center"><img src="docs/assets/banner.svg" alt="Churn Prediction — Turn account activity into retention signals." width="100%"></p>

<p align="center"><img src="docs/assets/badges/python.svg" alt="python" height="28"> <img src="docs/assets/badges/pandas.svg" alt="pandas" height="28"> <img src="docs/assets/badges/scikit-learn.svg" alt="scikit-learn" height="28"> <img src="docs/assets/badges/jupyter.svg" alt="jupyter" height="28"></p>

<p align="center"><strong>An exploratory notebook for understanding customer churn through tabular analysis, visualization, and logistic-regression baselines.</strong></p>

## Overview

An exploratory notebook for understanding customer churn through tabular analysis, visualization, and logistic-regression baselines.

### Why it matters

The project shows how customer attributes and activity patterns can be shaped into a clear analytical workflow for retention-focused questions.

## Key features

- Customer and transaction exploratory analysis
- Missing-value handling and categorical encoding
- Derived account-activity features
- Logistic-regression baseline experiments

## Architecture

```mermaid
flowchart LR
  A[Customer CSV] --> B[Exploration]
  B --> C[Feature preparation]
  C --> D[Train / test split]
  D --> E[Logistic regression]
  E --> F[Model review]
```

## Technology stack

**python** · **pandas** · **scikit learn** · **jupyter**

## Getting started

Open `Churn_Prediction.ipynb` in a compatible Jupyter environment with the repository CSV available in the working directory. Run cells in order after reviewing the preprocessing choices.
