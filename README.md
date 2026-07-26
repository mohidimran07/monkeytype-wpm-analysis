# Monkeytype WPM & Performance Analysis

A statistical and time-series evaluation of longitudinal personal typing performance data using Python.

## Overview
This project analyzes **980+ completed typing tests** to evaluate skill acquisition, track performance progression over time, and quantify the relationship between typing speed (WPM) and accuracy.

## Key Insights
* **Learning Curve & Breakout:** Applied a 50-test rolling average to smooth out daily variance, capturing an initial growth curve, a prolonged plateau phase, and a recent structural speed breakout (~170 WPM moving average).
* **Speed vs. Accuracy Trade-Off:** Mapped an upward-sloping trend line demonstrating an outward shift in the personal Production Possibility Frontier (PPF).
* **Multivariate OLS Regression:** Modeled accuracy against speed and cumulative experience using `statsmodels` ($R^2 = 0.520, p < 0.01$). Controlled for practice effects to eliminate omitted variable bias.

## Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Visualizations:** Matplotlib, Seaborn
* **Econometric/Statistical Modeling:** Statsmodels (OLS Regression)
