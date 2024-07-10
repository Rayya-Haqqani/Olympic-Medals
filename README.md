# Olympic-Medals
This project builds a model to predict the likelihood of an Olympic team winning new medals based on their previous performances

1. Loads a dataset about Olympic teams and their medal counts.
2. Explores the data by checking correlations, creating scatter plots, and visualizing the distribution of medal counts.
3. Checks for and drops null values from the dataset.
4. Builds a Linear Regression model to predict the number of medals based on the number of athletes and previous medal counts.
5. Splits the data into training (before 2012) and testing (2012 and later) sets.
6. Makes predictions on the test set and measures the mean absolute error.
7. Analyzes the model's performance by comparing the predicted and actual medal counts for specific teams (USA and India).
8. Calculates the error ratio (mean absolute error divided by mean medal count) for each team and visualizes its distribution.
