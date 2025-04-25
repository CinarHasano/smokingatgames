# Gaming Behavior and Cigarette Consumption

## Motivation

The goal of this project is to explore whether certain daily habits have an effect on cigarette consumption during gaming. In particular, the project investigates if longer gaming sessions and shorter sleep durations are associated with smoking more cigarettes. This study aims to uncover behavioral patterns and possible dependencies between gaming and lifestyle factors.

## Dataset

The dataset is self-recorded and spans from March 10 to April 26. It contains the following variables:
- **Date**: Day of observation
- **Games Played**: Number of games played on that day
- **Game Hours**: Total hours spent playing games
- **Cigarettes**: Number of cigarettes smoked while gaming
- **SleepHours**: Estimated sleep duration (hours)
- **StudyHours**: Estimated hours of academic work
- **MealCount**: Number of meals
- **SocialHours**: Estimated time spent socializing (hours)

Only the first three columns were manually recorded; the rest were synthetically generated for analysis completeness.

## Exploratory Data Analysis (EDA)

- Cigarette consumption ranges from 5 to 13 per day, with an average near 9.
- Most players played between 2 to 5 games a day.
- Sleep duration mostly varied between 6 and 8 hours.
- Strong positive correlation observed between Game Hours and Cigarettes smoked.
- Visual analysis (scatter plot) supported this strong linear relationship.

## Hypothesis Testing

**Hypothesis 1:**
> There is a statistically significant relationship between the amount of time spent gaming and the number of cigarettes smoked during gaming.

**Hypothesis 2:**
> There is a statistically significant relationship between sleeping less and smoking more while gaming.

**Tests Used:** Pearson correlation and linear regression.

- **Hypothesis 1 Results:**
  - Pearson r = 0.85, p-value = 2.63e-11 ‚Üí Strong positive and statistically significant correlation.
  - Regression: `Cigarettes = 1.3958 + 1.7882 √ó GameHours`
  - R¬≤ = 0.724, meaning 72% of the variation in cigarette consumption is explained by game time.

- **Hypothesis 2 Results:**
  - A weaker negative correlation between SleepHours and Cigarettes was observed.
  - The result suggests that people who sleep less may smoke slightly more during gaming, but the relationship is less pronounced.

## Limitations and Future Work

- Sleep, study, and social data were not collected in real-time; they were estimated.
- The study only considers one participant; generalizability is limited.
- In the future, data from multiple individuals and additional behavioral factors (e.g., stress level, caffeine intake) could enhance the analysis.

## Conclusion

The analysis confirms that gaming duration is strongly correlated with cigarette consumption. Additionally, there is a weak negative relationship between sleep and smoking, indicating a possible influence of sleep deprivation. These insights may be useful in understanding behavioral dependencies and designing interventions for healthier gaming habits.
