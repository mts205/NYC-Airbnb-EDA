Overview
This document outlines the steps taken to handle missing values in the NYC Airbnb dataset.
1. Visualizing Missing Values
A heatmap was created to visualize the missing values in the dataset.
2. Columns with High Missingness
license: Dropped due to ~99.99% missing values.
3. Columns with Low Missingness
name: Imputed missing values with "Unknown". Flag column name_missing created.
host_name: Imputed missing values with "Unknown". Flag column host_name_missing created.
4. Date-Related Columns
last_review: Imputed missing values with NaT (Not a Time) to indicate missing datetime values. Flag column last_review_missing created.
reviews_per_month: Imputed missing values with 0.0 to indicate no reviews during that period. Flag column reviews_per_month_missing created.
5. Verification
Flag columns were verified to ensure accurate missing value tracking.
6. Summary
The dataset is now ready for further analysis.