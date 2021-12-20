# Predict the first Innings score in a ODI

- 1. Load the dataset from the csv file.
- 2. Use “groupby” operation, to find the average number of runs, scored by each country,
and represent it on a bar graph.
- 3. Handle Missing values:

       a.  If there are null values in continuous numerical column, replace the null values by
the mean of that column

       b.  If there are null values in ordinal numerical column, replace the null values by the
mode of that column

       c.  If there are null values in categorical column, replace the null values by the mode
of that column

       d.  If more than 50%the values in a column are null, then drop that entire column
- 4. Remove the columns, that you think, do not contribute to the total score, in the first
innings.
- 5. Convert the categorical columns (if any), to numeric, using one hot encoding/ dummy
encoding.
- 6. Pick “total” column, as the target variable
- 7. Select the relevant features.
- 8. Perform train-test-split
- 9. Perform Feature scaling
- 10. Use

       a.   Use Linear Regression

       b.   Use Decision Tree Regression

       c.   Use Random Forest Regression

- 11. Evaluate the model
- 12. Apply prediction
