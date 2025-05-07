# Gaming Behavior and Its Effects on Sleep and Cigarette Consumption

## Motivation

The goal of this project is to investigate how gaming habits may affect daily life activities such as sleeping and smoking. Specifically, this project focuses on whether playing games reduces sleep duration and whether gaming increases the number of cigarettes smoked while gaming. These questions reflect a personal curiosity about how gaming sessions may shape other behavioral patterns.

## Dataset

The dataset was collected between March 10 and April 26. The data was carefully recorded based on real sources:

- **Games Played and Game Hours**: Collected from Riot Games' API statistics page, providing accurate information about the number of games played each day and their durations.

- **Cigarettes Smoked**: Recorded manually based on personal daily tracking during gaming sessions.

- **Sleep Hours**: Measured and recorded using Apple Watch sleep tracking data, ensuring realistic and accurate information.

The dataset contains the following columns:

- **Date**: Day of observation
- **Games Played**: Number of games played
- **Game Hours**: Total hours spent playing games
- **Cigarettes Smoked**: Number of cigarettes smoked while gaming
- **Sleep Hours**: Total sleep duration (hours)

## Exploratory Data Analysis (EDA)

- The number of cigarettes smoked while gaming shows a variable pattern, typically between 6 and 13.
- Sleep Hours mostly range from 5 to 8 hours.
- Game Hours vary widely, generally between 1 and 5 hours per day.
- A correlation heatmap and scatterplots were used to explore potential relationships.

## Hypotheses

**Hypothesis 1:**
> Does playing games reduce my sleep duration?

**Hypothesis 2:**
> Does playing more games increase the number of cigarettes smoked while gaming?

## Hypothesis Testing

**For Hypothesis 1 (Games vs Sleep):**
- A negative correlation was tested using Pearson correlation.
- The analysis suggests whether playing more games is statistically associated with reduced sleep.

**For Hypothesis 2 (Games vs Cigarettes):**
- A positive correlation was tested using Pearson correlation.
- The analysis investigates if gaming longer increases cigarette consumption during sessions.

## Limitations and Future Work

- The study is based on a single individual's behavior.
- Other factors (such as stress or social environment) are not included and could be considered in future research.
- Future studies could gather data from multiple individuals to improve generalizability.

## Conclusion

The analysis provides insights into the connection between gaming habits and other daily activities. The project highlights potential impacts on sleep and smoking behavior, suggesting possible patterns that could be important for understanding behavioral health.