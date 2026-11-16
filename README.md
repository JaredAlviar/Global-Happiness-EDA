# World Happiness Report — Exploratory Data Analysis

An exploratory data analysis (EDA) of the World Happiness Report dataset (157 countries, 13 variables) using Python in Google Colab.

## Objectives
1. **Top-Tier Drivers:** Analyze the distributions and outliers of economic, social, and health factors among the top 25% happiest nations.
2. **Happiness Tiers:** Group countries into Low, Medium, and High happiness tiers ("pd.qcut") to examine how social support ("Family") and "Health (Life Expectancy)" move together.
3. **Regional Comparison:** Compare average "Happiness Score" across global regions against the global mean ("5.38").

## Key Findings
* **Regional Gaps:** **Australia and New Zealand** ("7.32") and **North America** ("7.25") lead the world well above the "5.38" global mean, while **Sub-Saharan Africa** ("4.14") and **Southern Asia** ("4.56") record the lowest regional averages.
* **Top 25% Happiest Nations:** High-ranking countries consistently combine strong GDP per capita, social support, and life expectancy with minimal downward outliers.
* **Social Support vs. Health:** Overall, "Family" and "Health" show a moderate-to-strong positive relationship. While countries in the **Low** tier scatter widely with little internal correlation, **Medium** and **High** tier nations cluster tightly in the upper-right quadrant.

## Tools Used
* Python ("pandas, "numpy", "matplotlib", "seaborn")
* Google Colab / Jupyter Notebook
