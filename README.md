# Sleep Efficiency Analysis
## Project Overview
This project investigates factors influencing sleep efficiency (the ratio of actual sleep time to total time spent in bed) using statistical analysis and data visualization. The goal is to identify patterns that could help improve sleep quality.

## Key Findings
### Sleep Patterns
- Strong positive correlation between deep sleep percentage and sleep efficiency
- Left-skewed distribution: Most individuals cluster around 0.9 sleep efficiency

### Bedtime Impact
🔍 Hypothesis Test (Mann-Whitney U Test):
- H₀: No difference in efficiency between before/after midnight bedtimes
- H₁: Before-midnight sleepers have higher efficiency
- Result: Statistically significant support for H₁ (p < 0.05)

### Exercise Frequency
🏋️ Kruskal-Wallis Test revealed:
- H₀: No difference across exercise frequency groups (0-5)
- H₁: At least one group differs
- Result: Rejected H₀ - Exercise frequency affects sleep efficiency

## Technologies Used
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## Dataset Features
- Sleep efficiency percentage
- Bedtime/wakeup times
- Deep sleep percentage
- Exercise frequency (0-5 scale)
- Additional lifestyle factors

## Statistical Insights
- Used non-parametric tests (Mann-Whitney U, Kruskal-Wallis) due to non-normal data distribution
- Visualized through:
    - Correlation matrices
    - Box plots (before/after midnight comparison)
    - Violin plots (exercise frequency distribution)

## Recommendations
💤 Prioritize deep sleep quality through sleep hygiene

⏰ Aim for before-midnight bedtimes

🚴 Moderate exercise (3-5x/week) correlates with better efficiency

## Future Work
- Machine learning models to predict sleep efficiency
- Time-series analysis of sleep patterns
- Expanded dataset with more lifestyle variables





