# Week-2
🌍 Carbon Emission Prediction – Week 2
Internship @ AICTE – Stage 2: Data Exploration & Visualization

📘 Notebook Overview
This week focuses on data exploration, visualization, and hypothesis testing for global CO₂ emissions. We conduct feature engineering, derive new insights through visualizations, and define the groundwork for predictive modeling.

🛠️ Tasks Completed
🔹 1. Introduction & Data Setup
Imported necessary libraries and loaded the dataset

Documented data sources and noted abbreviations/units of features

🔹 2. Hypothesis Definition
Goal: To understand how features like energy use, population, GDP, and land use influence CO₂ emissions

Hypothesis: CO₂ emissions can be predicted from country-level features including energy use, GDP, and land metrics.

🔹 3. Feature Engineering
Created new features like total energy use (en_ttl)

Removed redundant or highly-missing features

Chose the most informative units (e.g., per capita vs per GDP)

🔹 4. Data Visualization & Analysis
Plotted:

Global average CO₂ emissions over time with confidence intervals

Scatter plots showing relationship between population and total CO₂ emissions

Correlation heatmaps between all features

Histograms and outlier detection for key metrics

🔹 5. Insights & Observations
Global CO₂ emissions per capita are stable (~4.3–4.9 metric tons) between 1991–2008

Significant variability exists across countries (e.g., developing vs developed)

Strong correlation observed between energy use and CO₂ emissions

Population size influences total emissions, but not per capita metrics

Non-linear patterns and country clusters suggest use of tree-based models

📊 Key Visualizations
📈 Global Emissions Trend (1991–2008)
Blue Line: Average CO₂ per capita

Shaded Area: Variability among countries
🔍 Reveals a stable trend globally with high country-level disparities

🌐 CO₂ vs Population
Scatter plot showing a positive correlation

High-emission countries align with population giants like China, India, USA

🔥 Correlation Heatmap
Strongest correlations seen with:

CO₂ per capita ↔ Energy per capita

GDP & FDI ↔ CO₂ emissions

💡 Conclusions
Retain CO₂ emissions per capita and energy use per capita for modeling

Remove population features due to weak influence on normalized emission metrics

Outliers (e.g., UAE) need to be handled separately

Favor non-linear ML models (e.g., Random Forest) over linear ones due to complex dependencies and clustering
