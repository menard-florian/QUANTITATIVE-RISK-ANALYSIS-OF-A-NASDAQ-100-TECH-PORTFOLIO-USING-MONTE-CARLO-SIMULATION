# QUANTITATIVE-RISK-ANALYSIS-OF-A-NASDAQ-100-TECH-PORTFOLIO-USING-MONTE-CARLO-SIMULATION
Monte Carlo Risk Analysis – Nasdaq Tech Portfolio
Overview

This project applies Monte Carlo simulations to a Nasdaq technology portfolio composed of five equally weighted stocks: Apple, Microsoft, Tesla, Nvidia, and Amazon. The objective is to compute Value at Risk (VaR) and Expected Shortfall (ES) at 95% and 99% confidence levels for 1-day and 10-day horizons.

It is a long-term personal project that reflects my growing interest in quantitative finance and risk management.

Features

Data collection from Yahoo Finance using yfinance

Computation of daily log-returns, covariance, and correlation matrices

Implementation of 100,000-path Monte Carlo simulations

Estimation of VaR and ES at different confidence levels and horizons

Comparison between Gaussian and Student-t distributions to account for fat tails

Visualization of return distributions, risk measures, and correlation heatmaps

Key Insights

High correlations among technology stocks result in limited diversification.

Gaussian models tend to underestimate tail risks.

Student-t distributions provide a more conservative and realistic view of extreme market events.

Monte Carlo methods are effective for modeling uncertainty and stress testing portfolios.
