# time-series-Explainability

## What has been done so far?
1- Dataset is found on Kaggle
2- Dataset processed to be easier "daily" dataset instead of "hourly"
3- To do training, a typical sliding windows (5 days window) style dataset is created by the simplified dataset
4- A simple (but well performing) RandomForestRegressor is being used for predictions
5- SHAP has been used to explain the most effective columns on dataset

## What is next?
1- Working on the dataset, to remove unnecesarry parts AND/OR add more parts
2- Normalize the columns on the dataset smartly, to have more robust model
3- Improve SHAP usage, to explain the predictions more deeply

the dataset location: https://www.kaggle.com/budincsevity/szeged-weather
-efe ergün.
