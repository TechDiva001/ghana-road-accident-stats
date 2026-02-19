# Road Accident Analysis in Ghana

## 📌 Project Overview

This project analyzes road accident data in Ghana using statistical and mathematical foundations, rather than machine learning models.

The goal is to understand patterns, variability, and relationships in road accidents and fatalities across time, regions, and urban–rural classifications, and to communicate these insights clearly through statistics and visualizations.

This project is intentionally statistics-driven and written to be human-readable, so that both technical and non-technical readers can follow the reasoning step by step.

## 🎯 Problem Context

Road accidents remain a major public safety concern in Ghana, affecting lives, infrastructure, and economic productivity.

Before building predictive or machine learning systems, it is critical to first answer foundational questions:

1. How do accident counts behave statistically?
2. Are observed differences real or just random variation?
3. Which regions or settings show significantly higher risk?
4. Can we trust the averages we compute from real-world data?

*This project focuses on answering these questions using statistics.*

## 🔍 Research Questions

The analysis is structured around the following questions:

1. How have road accident cases and fatalities changed over time?
2. How do accident levels differ across regions in Ghana?
3. Are urban areas statistically more dangerous than rural areas?
4. How variable are accident outcomes, and are there extreme patterns?
5. Which statistical measures best summarize road accident data?

## 📊 Mathematical & Statistical Frameworks Used

This is a statistics-first project, built on the following foundations:

1. Descriptive statistics (mean, spread, skewness)
2. Probability distributions (Poisson behavior of accident counts)
3. Central Limit Theorem
4. Inferential statistics (T-tests)
5. ANOVA (comparison across multiple regions)
6. Correlation and covariance analysis
7. Rate normalization (per 100,000 population)
8. Trend analysis over time
9. Matrix-based thinking behind statistical computation

*No machine learning models are used in this analysis.*

## 🧠 What This Notebook Does

Inside the notebook, you will find:

1. Clear explanations (Markdown) of why each statistical method is used
2. Step-by-step data cleaning and preparation
3. Statistical tests backed by interpretation (not just numbers)
4. Visualizations that support and explain the findings
5. Code comments explaining each step for learning purposes

## 📁 Project Files

1. ghana_road_accidents_2010_2025.csv (Road accident dataset covering incidents, fatalities, population, region, and urban–rural classification.)

3. Road_Accident_Analysis_Ghana.ipynb (Jupyter Notebook containing the full statistical analysis, explanations, and visualizations.)

4. README.md (Project documentation.)

5. requirements.txt (Python dependencies.)

## 🛠️ Technical Stack

Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Google Colab

## 🚀 Installation & Usage

```bash

## Clone the Repository
git clone https://github.com/TechDiva001/ghana-road-accident-stats.git
cd road-accident-analysis-ghana 

## Install Dependencies
pip install -r requirements.txt

## Run the Notebook
jupyter notebook

