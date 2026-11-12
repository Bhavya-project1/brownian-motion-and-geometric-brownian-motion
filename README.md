# Brownian Motion and Geometric Brownian Motion

An Excel-based quantitative-finance exercise exploring two foundational stochastic processes used in continuous-time financial modelling: **Brownian motion** and **geometric Brownian motion (GBM)**.

## Brownian Motion

A standard Brownian motion `W_t` has independent, normally distributed increments:

`W_{t+Δt} - W_t ~ N(0, Δt)`

It is a core building block for stochastic differential equations.

## Geometric Brownian Motion

GBM models a positive stochastic quantity, such as an idealised equity price:

`dS_t = μS_t dt + σS_t dW_t`

Its exact solution is:

`S_t = S₀ exp[(μ - σ²/2)t + σW_t]`

where `μ` is drift and `σ` is volatility.

## Repository Contents

- `Brownian-Motion-1.xlsx` — spreadsheet-based exercise.

## How to Use

1. Download and open the workbook in Microsoft Excel.
2. Review the time-step, drift, volatility, and initial-value assumptions.
3. Inspect random increments and simulated process paths.
4. Recalculate to generate alternative paths.
5. Compare Brownian motion and GBM behaviour under different parameter choices.

## Applications

Asset-price dynamics · Stochastic differential equations · Market-scenario simulation · Drift and diffusion · Foundations for derivative pricing and risk models

## Limitations

GBM is a useful baseline but does not capture many empirical features of financial returns, including jumps, volatility clustering, stochastic volatility, and heavy tails.

## Disclaimer

Educational stochastic-process modelling only. Not investment advice.
