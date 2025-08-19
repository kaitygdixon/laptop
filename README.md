Laptop Pricing Analysis

Overview
This Jupyter Notebook explores a dataset of laptops to analyze how different hardware specifications (CPU, GPU, RAM, screen size, weight, etc.) affect laptop prices. The analysis includes descriptive statistics, visualizations, correlation testing, and pivot-table heatmaps.

Data
Source: IBM Developer Skills Network – Coursera

Content: Laptop specifications including CPU frequency, CPU cores, GPU type, screen size, weight, and price.

Objectives
Summarize the dataset and key descriptive statistics.
Visualize how specific features (CPU frequency, screen size, weight) relate to laptop price.
Calculate correlations (Pearson coefficient & p-values) between features and price.
Use pivot tables and heatmaps to explore relationships between GPU, CPU cores, and pricing trends.

Notebook Structure
Data Loading
Import CSV dataset into a Pandas DataFrame.
Descriptive Statistics
Generate summary statistics for all features.
Exploratory Visualizations
Regression plots of price vs. CPU frequency, screen size, and weight.
Correlation Analysis
Compute correlations and statistical significance between numerical features and price.
Pivot Tables & Heatmaps
Visualize mean prices across GPU and CPU core combinations.

Requirements
Install the required Python packages before running the notebook:
pip install pandas numpy matplotlib seaborn scipy jupyter

Usage
Clone or download this repository.
Install the requirements.
Open the notebook:
jupyter notebook "Laptop (1).ipynb"
Run cells in order to reproduce the analysis.

Key Insights (Example Findings)
Stronger GPUs and more CPU cores generally increase laptop prices.
CPU frequency and screen size show positive correlations with price.
Lightweight laptops sometimes command higher prices depending on other specifications.

Next Steps
Expand to predictive modeling (e.g., regression models to estimate price).
Add categorical analysis (brand, operating system).
Develop interactive dashboards for deeper data exploration.
