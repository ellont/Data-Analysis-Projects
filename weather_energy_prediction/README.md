## Weather-based Energy Consumption Prediction
Required python version v3.11 or above

### Data Cleaning and Transformation
Refer to _data_cleaning.ipynb_
1. Missing values
    * Replacing missing data with NaN when suitable
    * Imputation (Linear interpolation & Mode)
    ![linear_Interpolation_1.jpg](/images/linear_Interpolation_1.JPG)
    ![linear_Interpolation_2.jpg](/images/linear_Interpolation_2.JPG)
    * Ignore/Accept
2. Transform
    * Covernt columns to appropriate data types

### Prediction Models
Refer to _data_analysis.ipynb_

1. Determine correlation
    * Seasonality
    ![season.jpg](/images/season.JPG)
    * Pearson
    ![pearson.jpg](/images/pearson.JPG)
    * Mutual Information
    ![mutual_info.jpg](/images/mutual_info.JPG)
    * Entropy
    ![entropy.jpg]([/images/entropy.JPG](https://github.com/ellont/Data-Analysis-Projects/blob/main/weather_energy_prediction/images/entropy.JPG))
2. Linear Regression Model (kfold)
3. Decision Tree Model
4. KNN Classification model - PCA
5. KNN Classification model - Greedy feature selection approach
