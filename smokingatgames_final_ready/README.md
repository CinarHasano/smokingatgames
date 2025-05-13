# Gaming Behavior and Its Effects on Sleep and Cigarette Consumption

## Motivation

This project aims to investigate the behavioral effects of gaming on two major aspects of daily life: sleep duration and cigarette consumption. The objective is to determine whether playing more games reduces sleep time and whether it increases the number of cigarettes smoked during gaming sessions. These questions arise from a personal interest in understanding the broader impact of habitual gaming.

## Dataset

The data was collected between March 10 and April 26 and includes daily records of:

- **Date**: The day of observation
- **Games Played**: Total games played per day
- **Game Hours**: Total hours spent playing games
- **Cigarettes Smoked**: Number of cigarettes smoked while gaming
- **Sleep Hours**: Total sleep duration per day

### Data Sources

- **Game data** was retrieved from Riot Games’ public match history tools.
- **Sleep data** was recorded using Apple Watch.
- **Cigarette consumption** was logged manually.

## Exploratory Data Analysis (EDA)

The EDA process included:

- Descriptive statistics and correlation matrix
- Scatterplots to visualize relationships
- Distribution analysis using histograms

### Outlier Detection

The IQR method was used to detect outliers in the dataset. The results showed that the number of outliers was **zero**, indicating a consistent dataset. This was also confirmed with visual inspection using boxplots.

## Hypotheses

### Hypothesis 1:
> Does playing more games reduce sleep duration?

### Hypothesis 2:
> Does playing more games increase the number of cigarettes smoked while gaming?

## Hypothesis Testing

For both hypotheses, Pearson correlation tests and linear regression models were applied.

- Hypothesis 1 tested the relationship between **Game Hours** and **Sleep Hours**
- Hypothesis 2 tested the relationship between **Game Hours** and **Cigarettes Smoked**

## Conclusion

The findings of this study highlight potential connections between gaming intensity and other health-related behaviors. The absence of outliers strengthens the reliability of the dataset. These results can be used to guide future self-monitoring or behavioral research, especially in contexts where gaming habits may influence lifestyle choices.
