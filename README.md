# Global-Environmental-Dynamics-EKC-Analysis
An econometric study of population aging impacts on CO2 emissions using the Environmental Kuznets Curve (EKC) framework. Implemented in Python with Panel Data analysis.



Does Population Aging Affect CO₂ Emissions?
A Global Study Based on the Environmental Kuznets Curve (EKC) Framework
# Project Overview

This project investigates the long-run relationship between population aging, economic development, and CO₂ emissions using a global panel dataset of 165 countries from 2010 to 2020. The study is grounded in the Environmental Kuznets Curve (EKC) framework and examines whether demographic structure—particularly population aging—acts as a driver or mitigator of environmental degradation.

Unlike standard regression approaches, this work applies a rigorous econometric pipeline designed for non-stationary panel data to ensure robust long-term inference.

* Methodology

The empirical strategy follows a structured econometric framework commonly used in advanced environmental economics research:

#  Data Structure
Panel dataset: 165 countries
Time period: 2010–2020
Observations: 1,190+
Data sources: World Bank, Our World in Data
🧪 Econometric Pipeline

*  Panel Unit Root Tests

Levin–Lin–Chu (LLC)
Im–Pesaran–Shin (IPS)
Maddala–Wu (MW)
Cross-sectionally augmented IPS (CIPS)

These tests ensure stationarity and prevent spurious regression issues.

* Panel Cointegration Analysis

Pedroni cointegration test (heterogeneous dynamics)
Kao cointegration test (homogeneous long-run relationship)

These tests confirm the existence of long-run equilibrium relationships among variables.

* Long-Run Estimation

Fully Modified Ordinary Least Squares (FMOLS)
Dynamic OLS (DOLS)

These estimators correct for endogeneity, serial correlation, and non-stationarity in panel settings.

# Model Specification

The study tests both nonlinear income–emissions relationships and demographic effects:

Quadratic EKC: inverted U-shape
Cubic EKC: N-shaped relationship

Key explanatory variables include:

GDP per capita (linear, squared, cubic)
Energy consumption
Renewable energy usage
Population structure (young, working-age, elderly)
Sectoral structure (manufacturing, services)

The model is estimated for:

 Global sample,High-income countries, Low-income countries, 
# Key Findings
* Environmental Kuznets Curve (EKC)
Global results confirm a nonlinear relationship between income and CO₂ emissions.
Evidence supports both inverted U-shaped and N-shaped EKC patterns depending on model specification.
High-income countries exhibit a clearer N-shaped relationship.
Low-income countries remain in the upward (emissions-increasing) stage of the EKC.
* Population Aging Effects
In high-income countries:
Elderly populations are associated with lower transportation emissions
Younger populations increase mobility-related emissions
In low-income countries:
All age groups contribute positively to emissions due to limited infrastructure and energy inefficiency
* Energy and Structural Effects
Energy consumption is a strong positive driver of emissions
Renewable energy significantly reduces emissions across all models
Industrial structure (manufacturing and services) shows heterogeneous effects depending on country income level
  * Economic Contribution

This study extends the traditional EKC and IPAT frameworks by incorporating population aging as a key explanatory variable. It demonstrates that demographic structure is as important as income in shaping long-term environmental outcomes.

#Key contributions:

Integrates demographic aging into EKC modeling
Uses robust panel econometric techniques (FMOLS, cointegration)
Provides global and income-group comparisons
Separates residential and transportation emissions for deeper insight

# Summary

Overall, the findings show that economic growth alone is not sufficient to reduce carbon emissions. Environmental outcomes depend strongly on both technological transitions and demographic structure. Aging populations reduce emissions in advanced economies but not necessarily in developing countries, highlighting the importance of context-specific environmental policy design.
