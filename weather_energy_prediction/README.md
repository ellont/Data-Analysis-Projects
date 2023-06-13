## Weather-based Energy Consumption Prediction
Required python version v3.11 or above

### Data Cleaning and Transformation
Refer to _data_cleaning.ipynb_
1. Missing values
    * Replacing missing data with NaN when suitable
    * Imputation (Linear interpolation & Mode)
    ![linear_Interpolation_1.jpg](/image/linear_Interpolation_1.jpg)
    ![linear_Interpolation_2.jpg](/image/linear_Interpolation_2.jpg)
    * Ignore/Accept
2. Transform
    * Covernt columns to appropriate data types

### Prediction Models
Refer to _data_analysis.ipynb_

1. Determine correlation
    * Seasonality
    ![season.jpg](/image/season.jpg)
    * Pearson
    ![pearson.jpg](/image/pearson.jpg)
    * Mutual Information
    ![mutual_info.jpg](/image/mutual_info.jpg)
    * Entropy
    ![entropy.jpg](/image/entropy.jpg)
2. Linear Regression Model (kfold)
3. Decision Tree Model
4. KNN Classification model - PCA
5. KNN Classification model - Greedy feature selection approach