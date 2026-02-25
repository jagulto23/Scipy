# Scipy
Analyzed NBA Kaggle data in Python using Pandas, NumPy, and SciPy: filtered regular-season stats, identified the longest-tenured player, calculated 3-point accuracy, performed regression and integration, interpolated missing seasons, and ran statistical tests.

# Part 1
The dataset was filtered to include only NBA regular season records.

The player with the most regular seasons was identified using group-by season counts.

Three-point accuracy was calculated for each season using 3PM/3PA.

A linear regression model was fitted to analyze the trend in accuracy over time.

The average accuracy was estimated by integrating the regression line across seasons and dividing by the season range.

This predicted average was compared with the player's actual average three-point accuracy.

Missing seasons (2002–2003 and 2015–2016) were estimated using linear interpolation between surrounding seasons.

# Part 2
Comparison of Statistics

The mean of FGA (Field Goals Attempted) is higher than FGM (Field Goals Made) because players attempt more shots than they successfully make.

The variance of FGA is typically larger since attempts vary more between players and games.

Skewness indicates whether the distribution is biased toward higher or lower values.

Kurtosis describes how concentrated the values are around the mean.

Comparison of T-tests

The relational (paired) t-test compares FGM and FGA for the same observations, meaning each made shot corresponds to a specific number of attempts.

The regular independent t-test treats the two columns as unrelated samples.

Because FGM and FGA are naturally related (made shots come from attempts), the paired t-test is more appropriate and typically produces a stronger statistical relationship.

# Generative AI 
I used AI to guide my analysis of the NBA dataset in Python. AI helped troubleshoot code errors, explain statistical methods, and provide examples for regression, integration, interpolation, and t-tests, helping me complete the assignment correctly.
