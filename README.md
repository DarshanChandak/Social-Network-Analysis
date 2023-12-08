# Social-Network-Analysis
Time Series Data Imputation and Analysis for Geolife Trajectory Dataset. <br>
Formal Project in 3-2 and 4-1 under Dr. Apurba Das at BITS Pilani, Hyderabad Campus.

  Missing data in time series data is a pervasive problem that puts obstacles in the way of
advanced data analysis. A popular solution is data imputation, where the fundamental challenge
is determining what values should be filled in the place of the missing values.
In this project, a method of Data Imputation has been successfully performed for the Geolife
Trajectory Dataset. To accomplish this, firstly, the data is flattened for each user based on time
value. The weight values are generated based on the number of occurrences of a particular
(latitude, longitude) pair in a specific time interval across all days for a particular user. Finally,
using these weight values, a weighted random sampling is carried out on the pre-processed data
to fill out the missing values for that user.
Then, clusters are formed for each user using the DBSCAN (Density-Based Spatial Clustering of
Applications with Noise) Algorithm. Clustering is carried out based on Latitude and Longitude
values for the user across all days on raw and processed data. Also, the Goodness Score of the
Clustering, i.e., the Silhouette score, is calculated for each user. After this, a similarity score is
calculated for each pair of users using the Jaccard Similarity Metric.
