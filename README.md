# Liga Leumit 2025/26 — Statistical Prediction Model

An interactive dashboard for predicting Israeli Premier League outcomes using machine learning.

## Dashboard

[View Dashboard](https://pilee11.github.io/liga-dashboard/)

## Model Code

[View on Colab](https://colab.research.google.com/drive/1KZ7A3nqXF94hzQaDSrrCpufMQ4hjo7mD#scrollTo=CtDFCYFkK0pp)

## Prediction Targets

- Championship winner
- European qualification (Top 4)
- Upper playoff (Top 6)
- Relegation to Liga Leumit

## Data

- Leagues: Israel, Greece, Cyprus — 2000 to 2025
- Source: Transfermarkt

## Model

- Algorithm: Logistic Regression
- Training: 5,095 matches
- Validation: 2023/24 and 2024/25 seasons

## Features

- Dynamic ELO ratings updated after each match
- Home win rate with Bayesian smoothing
- Cumulative goals scored and conceded rankings
- Historical league performance (last 3–20 seasons)
- Squad turnover rate

## How It Works

Each round, the model generates win probabilities for all four targets using in-season snapshot features. Mathematical filters ensure probabilities reflect what is still achievable given remaining fixtures.
