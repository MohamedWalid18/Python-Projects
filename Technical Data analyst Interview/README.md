# Overview
  This dataset was sent as an evaluation procedure for a data analyst applicant covering the techincal part of the job where applicants were provided with a set of questions (12 Q) to test their coding and problem solving skills.


# Data Description
  A sample survey Data(sample survey.xlsx) is provided for analysis.Samples were collected over a period of 9 days where the respondents were asked questions related to elections.
Survey weights are in the 'weight' column. The description for each column is provided in the excel sheet under tab named 'Description'. Applicants are requested to use python-pandas for all data manipulation and matplotlib for any plotting related questions. Applicants are expected to not use for-loops or any kind of iterations for solving the questions. Use built-in pandas functions only.


# Questions
- Question 1 - Load the dataset into a pandas dataframe. Name the variable as “survey”.
- Question 2 - How many samples were collected on each day?
- Question 3 - What proportion of the total respondents were aged less than 45?
- Question 4 - Create a new column in the dataframe “age_group”. This column should contain the age group the respondent belongs to. The age groups are 18-25, 25-40, 40-55 and 55+. The dataframe should look like this after the column creation.
- Question 5 - How many samples were collected for each age-group? Which age-group had the most samples?
- Question 6 - What proportion of the respondents had opted for the RJD party in both the Vote_Now and the Past_Vote questions?
- Question 7 - For each day of sample collection, determine the proportion of respondents who were fully satisfied with the performance of the CM. So if there were a total of 1000 samples on day 1 and 300 out of those said they were fully satisfied, then our answer for that day would be 0.3.
- Question 8 - In a similar fashion create a day-wise proportion of respondents that opted fully dissatisfied with their MLA. Create a line plot of the result with date on x-axis and proportions on the y-axis.
- Question 9 - Create a pivot-table (or crosstab) with index as Past_Vote, Column as Vote_Now and cell values as the count of samples.
- Question 10 - Repeat the above question with the cell values as the sum of “weight”.
- Question 11 - Create a dataframe by performing a group by over age_group and calculate the count of total samples under each age_group.
- Question 12 - Create a dataframe by performing a group by over age_group and finding the count of total samples for each age_group that opted for the JD(U) party in Vote_Now.
