# Task 01 - Distribution Analysis
# Task 01 — Distribution Visualization

## Objective
Visualize the distribution of a categorical variable (Gender) and a continuous
variable (Age) using the Titanic dataset.

## Dataset
Titanic passenger dataset (loaded via `seaborn.load_dataset("titanic")`)

## Charts

### Gender Distribution (Bar Chart)
![Gender Bar Chart](gender_bar_chart.png)

### Age Distribution (Histogram)
![Age Histogram](age_histogram.png)

## Observations
The dataset contains 577 male and 314 female passengers — roughly 65% male.
Age is right-skewed, with most passengers between 20–40 years old, mean age
~29.7 and median age 28. This suggests the Titanic's passengers skewed young
adult, with fewer children and elderly aboard.

## Tools Used
- Python
- pandas
- seaborn
- matplotlib
