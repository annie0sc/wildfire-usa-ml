# Classifying and Predicting the possibility of Wildfires in the U.S.

Wildfires are a huge liability to any country’s economy. It consumes houses, forests, and lives uncontrollably. I would like to find correlations between features such as the high temperatures in summer, forest density, winds present, latitudes and longitudes, and fire sizes. Hopefully, the results would be helpful to predict the possibility of a fire before it appears, which would help the local authorities to prepare for these fires prior to the accidents.

## Initial Goals

**The feature combinations that are useful are:** 
* fire_size & putout_time 
* fire_size & stat_cause_descr 
* fire_size_class, latitude, longitude
* Temp_pre_7, Wind_pre_7, Hum_pre_7, Prec_pre_7

<!-- ### My Output: 
* I am hoping to predict the possibility of wildfires before they happen to help the local authorities to be prepared. -->

### Datasets:
* The dataset used for this project is taken from Kaggle, link as follows:
https://www.kaggle.com/capcloudcoder/us-wildfire-data-plus-other-attributes 

*This is the dataset that I have used in the project*

* A second dataset is also from Kaggle, link as follows:
https://www.kaggle.com/rtatman/188-million-us-wildfires

## Conclusion

Alfter using many Machine Learning models for prediction and classification I have successfully understood how to predict the possibility of a fire in a particular area given the weather conditions of that place 7 days prior to the expected date. In addition to this, I have also classified the predicted fire into fire_size classes. This means the magnitude of the fire is also classified based on the data given.

## Reference Links
### MD Files:

1. [RAW_DATA](https://github.com/annie0sc/wildfire-usa-ml/blob/main/RAW_DATA.md)

1. [DATA](https://github.com/annie0sc/wildfire-usa-ml/blob/main/DATA.md)

1. [ANALYSIS - TECHNICAL RESULTS](https://github.com/annie0sc/wildfire-usa-ml/blob/main/ANALYSIS.md)

1. [CONCLUSION - NARRATIVE RESULTS](https://github.com/annie0sc/wildfire-usa-ml/blob/main/CONCLUSION.md)

### IPYNB Notebooks: 

1. [Initial Exploration of Dataset](https://github.com/annie0sc/wildfire-usa-ml/blob/main/initial_exploration.ipynb)

1. [Linear Regression](https://github.com/annie0sc/wildfire-usa-ml/blob/main/linear_regression.ipynb)

1. [Classification](https://github.com/annie0sc/wildfire-usa-ml/blob/main/Classification.ipynb)

1. [Data Analysis](https://github.com/annie0sc/wildfire-usa-ml/blob/main/Data%20Analysis.ipynb)