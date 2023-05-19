# Social-Network-Analysis
Formal Project in 3-2 BITS Hyderabad

Missing data in time series data is a pervasive problem that puts obstacles in the way of
advanced data analysis. A popular solution is data imputation, where the fundamental challenge
is determining what values should be filled in, in the place of the missing values.
In this project, a Time Series Data Imputation has been successfully been performed for Geolife
Trajectory Dataset. Morever, data is being analyzed for each individual user by converting the
latitude and longitude data into x and y coordinates. Then these x and y points are plotted on a
graph, and then a trajectory graph for a user is obtained for a particular day.
A codebase is formed where we can input the user number and the start and end date for that
particular user and get in resultant the imputed data for that user, and corresponding x and y
coordinates. We can get data for the user’s longitude and latitude values for the particular day in
a frequency of 30 minutes, even if this particular time’s value is missing in the original dataset.
We are using SAITS: Self-Attention-based Imputation for Time Series model by training it on
our geolife trajectory dataset for Time Series Data Imputation.
