Height and Weight Analysis
This project analyzes the relationship between height and weight using a provided dataset. It includes steps for data loading, hypothesis testing, normality checking, and correlation analysis.

Dataset:weightheight.csv
The dataset contains the following attributes:

Gender: Categorical variable indicating the gender of individuals.
Height: Continuous variable representing the height of individuals.
Weight: Continuous variable representing the weight of individuals.
Project Steps
Data Loading: Loads the data from the weightheight.csv file into a pandas DataFrame.
Hypothesis Testing: Formulates and tests hypotheses related to the relationship between height and weight using Pearson correlation and a t-test.
Normality Check: Assesses the normality of the distribution for height and weight variables using the Shapiro-Wilk test and histograms with KDE plots.
Correlation Analysis: Performs a correlation analysis between height and weight, calculates the Pearson correlation coefficient, and visualizes the relationship using a scatter plot with a fitted regression line and a heatmap of the correlation matrix.
Code Structure
The project is structured into several code cells, each addressing a specific step of the analysis:

Import Libraries: Imports necessary libraries like pandas, numpy, matplotlib, seaborn, and scipy.stats.
Load Dataset: Loads the weightheight.csv file.
Hypothesis Testing: Contains code for performing the Pearson correlation test and t-test.
Normality Check: Includes code for the Shapiro-Wilk test and generating histograms.
Correlation Analysis: Contains code for calculating the correlation matrix, generating a heatmap, and creating a scatter plot with a regression line.
Interpretation of Results
The initial hypothesis test showed a strong positive correlation between height and weight, with a statistically significant p-value, leading to the rejection of the null hypothesis.
Normality tests indicated that neither height nor weight distributions are perfectly normal, which is common with large datasets.
Correlation analysis confirmed the strong positive linear relationship between height and weight, as visualized in the scatter plot and heatmap.
