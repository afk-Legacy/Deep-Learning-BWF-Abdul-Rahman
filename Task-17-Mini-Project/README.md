## Census Data Cleaning and Analysis

As a new hire at the Census Bureau, you are tasked with cleaning and analyzing the data left by your predecessor, which is spread across multiple CSV files. Your boss wants you to create scatterplots and histograms by the end of the day. Follow these instructions to get the data into pandas and in a reasonable shape for visualization:

+ Inspect the data to create a scatterplot that shows average income in a state vs proportion of women in that state.
+ Open some of the census CSV files to check the file names and information they hold.
+ Load the data into a DataFrame and concatenate all DataFrames into one called `us_census`.
+ Check the DataFrame's `.columns` and `.dtypes`.
+ Look at the DataFrame's `.head()` to understand why some datatypes are objects instead of integers or floats.
+ Plan to convert columns into the appropriate types for manipulation.
+ Split the `GenderPop` column into `Men` and `Women` columns, convert both columns to numerical datatypes, and remove the M or F character in each entry.
+ Use matplotlib to create the scatterplot.
+ Check for null or NaN values by printing the column with the number of women per state.
+ Fill in those null or NaN values using pandas' `.fillna()` function.
+ As an estimate for the null or NaN values in the `Women` column, subtract the `Men` column from the `TotalPop` column.
+ Drop duplicates in the census DataFrame using the `.drop_duplicates()` function.
+ Make the scatterplot again to ensure it's perfect.
+ Create histograms of race data by converting columns to numerical format and filling null or NaN values with a reasonable estimate.
+ Check for duplicates again to ensure data accuracy.

Phew, you've impressed your boss on your first day of work! 🚀💻📊📈🔍💡💪
