# Exploring the Relationship between Drought,Food Insecurity and Violence Against Women in Kenyan Counties
# Project Overview

This project examines the relationship between food insecurity (IPC Phase 3+),Drought and violence against women (VAW) across Kenyan counties, with a focus on ASAL (Arid and Semi-Arid Lands) counties.

# The analysis explores:

Distribution of acute food insecurity (IPC Phase 3+).

Association between food insecurity and physical violence.

Differences in violence prevalence between ASAL and non-ASAL counties.

Whether IPC Phase 3+ should be treated as a continuous or categorical variable.

This project aims to contribute to understanding how structural vulnerability may intersect with gender-based violence outcomes.It also demonstrates the application of Python for data cleaning, exploratory analysis, visualization, and basic statistical interpretation in a humanitarian and public health context.

# Research Questions

How does IPC Phase 3+ prevalence vary across ASAL counties?

Is there an association between food insecurity and physical violence?

Do ASAL counties experience higher levels of violence compared to non-ASAL counties?

Should IPC Phase 3+ be modeled as a continuous indicator?

How does recent physical violence against women vary by drought severity?

# Data Sources

Kenya National Bureau of Statistics (KNBS): Violence Against Women indicators (12-month prevalence)

HDX : Integrated Food Security Phase Classification (IPC): Phase 3+ prevalence (ASAL counties)

NDMA Kenya : Drought classification data: Normal, Alert, Alarm

NDMA Kenya : County ASAL classification

All datasets were harmonized at the county level for 2022.

# Methods

Python: pandas, matplotlib, scipy

Data cleaning and encoding of categorical variables

Subsetting analysis to ASAL counties where IPC data are defined

Exploratory data analysis (EDA)

Visualization using Matplotlib (box plots, bar charts, scatter plots, histogram)

# Key Findings
1️⃣ Distribution of IPC Phase 3+

IPC Phase 3+ prevalence shows substantial variation across ASAL counties, ranging from low to high levels of acute food insecurity.
This heterogeneity supports treating IPC Phase 3+ as a continuous variable, as dichotomizing it would result in loss of information.

2️⃣ Food Insecurity and Physical Violence

A weak positive correlation was observed between IPC Phase 3+ and physical violence:
Correlation coefficient (r ≈ 0.17). This suggests:
Counties with higher food insecurity tend to report slightly higher physical violence
The association is modest.Food insecurity alone does not fully explain variation in violence outcomes

3️⃣ ASAL vs Non-ASAL Comparison

Average prevalence of both physical and sexual violence was slightly higher in non-ASAL counties compared to ASAL counties.This indicates:
Higher food insecurity does not automatically translate to higher average violence levels.
Structural and contextual factors likely play a role beyond food insecurity alone.

# Visualizations

The repository includes:

Distribution of IPC Phase 3+ in ASAL counties.

Scatter plot of IPC Phase 3+ vs Physical Violence.

Box plot of Physical Violence by Drought Level.

Bar chart comparing VAW in ASAL vs Non-ASAL counties.

All figures are located in the /figures folder.

# Limitations

The observed relationships are correlational, not causal.

GBV data are self-reported and likely underreported.

IPC data are only available for ASAL counties.

County-level aggregation may mask within-county heterogeneity.

# Why This Project Matters

This project highlights how data science can be applied to gender, health, and climate resilience challenges in development and humanitarian settings. It emphasizes ethical handling of sensitive data and responsible interpretation of statistical results.




