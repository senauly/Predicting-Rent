# Predicting Rent

## Problem Definition

The problem is to predict the rent of houses, apartments, and flats available for rent in India. The dataset used for this project includes information on almost 4700+ properties, including parameters such as BHK, Rent, Size, No. of Floors, Area Type, Area Locality, City, Furnishing Status, Type of Tenant Preferred, No. of Bathrooms, Point of Contact. The goal is to use this data to accurately predict the rent of a property, taking into account all relevant factors. This information can be useful for landlords, property managers, and potential tenants. The rent values in the dataset were converted from Indian rupees to Turkish Lira in order to understand the data better. Because I am not familiar with Indian currency and analyzing data with it was harder for me.

## Data Cleaning and Preprocessing

Data cleaning and preprocessing is an essential step in any data mining project. It involves identifying and correcting any errors, inconsistencies, and missing values in the dataset. This step also includes transforming and normalizing the data, so it is ready for further analysis. In this project, the dataset was initially reviewed for any missing or incorrect values and necessary corrections were made.
Outliers were identified and removed from the dataset. This was done to ensure that the data was representative of the population and that any extreme values would not skew the results of the analysis.
Additionally, categorical variables were converted into numerical ones using one-hot encoding. These steps were crucial in ensuring the accuracy and reliability of the final results.

## Results

I used 30% of my training dataset as a test dataset and tried different models using different metrics. According to the R2 score, Random Forest and XGBoost perform the best among the models I tried. They both have high R2 scores, which means they are able to explain a large percentage of the variation in the target variable.
Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) which indicate the model's performance in terms of the error between the predicted and actual values. In this case, Random Forest has lower MAE, MSE and RMSE compared to XGBoost. But the difference is not significant and XGBoost is faster than Random Forest. Random Forest or XGBoost can be selected according to needs.

