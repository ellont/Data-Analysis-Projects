## Weather-based Energy Consumption Prediction
Required python version v3.11 or above

### Data Cleaning and Transformation
Refer to _data_cleaning.ipynb_
1. Missing values
    * Replacing missing data with NaN when suitable
    * Imputation (Linear interpolation & Mode)

    ![linear_Interpolation_1.jpg](/https://github.com/ellont/Data-Analysis-Projects/blob/main/weather_energy_prediction/images/linear_Interpolation_1.JPG?raw=true)

    ![linear_Interpolation_2.jpg](/https://github.com/ellont/Data-Analysis-Projects/blob/main/weather_energy_prediction/images/linear_Interpolation_2.JPG?raw=true)
    * Ignore/Accept
2. Transform
    * Covernt columns to appropriate data types

### Prediction Models
Refer to _data_analysis.ipynb_

1. Determine correlation
    * Seasonality

    ![season.jpg](/https://github.com/ellont/Data-Analysis-Projects/blob/main/weather_energy_prediction/images/season.JPG?raw=true)
    * Pearson

    ![pearson.jpg](/https://github.com/ellont/Data-Analysis-Projects/blob/main/weather_energy_prediction/images/pearson.JPG?raw=true)
    * Mutual Information

    ![mutual_info.jpg](/https://github.com/ellont/Data-Analysis-Projects/blob/main/weather_energy_prediction/images/mutual_info.JPG?raw=true)
    * Entropy

    ![entropy.jpg](/https://github.com/ellont/Data-Analysis-Projects/blob/main/weather_energy_prediction/images/entropy.JPG?raw=true)
2. Linear Regression Model (kfold)
3. Decision Tree Model
4. KNN Classification model - PCA
5. KNN Classification model - Greedy feature selection approach