# Movie Industry Correlation Analysis

## Project Overview
This project explores a dataset of 7,500+ movies to identify which factors (budget, company, votes, etc.) have the strongest impact on gross revenue.

## Tech Stack
* **Python** (Pandas, NumPy)
* **Visualisation:** Seaborn, Matplotlib

## Key Findings
* **Strongest Predictors:** Movie Budget (0.75 correlation) and User Votes (0.63).
* **The Surprise:** Production Company reputation had a very low correlation (0.15) with financial success, disproving my initial hypothesis.

## Methodology
1. **Data Cleaning:** Handled null values and corrected data types using Pandas.
2. **Correlation Matrix:** Created a heatmap to visualize relationships between all variables.
3. **Numerization:** Converted categorical data into codes for deeper statistical analysis.
