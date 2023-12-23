# smartphones-models-insights

This repository shows an analysis of smartphone features that are predictive of higher ratings and higher prices via the "[Smartphone Models Dataset](https://www.kaggle.com/datasets/abdurrahman22224/smartphone-new-data)" published on Kaggle.  

The data and Jupyter Notebook have been added to the repo so that anyone can recreate the steps involved and add their own insights. 

## Use of:
* **Jupyter Notebook** 2023.03.0-daily+82.pro2
    * **Main Packages used:** pandas, numpy, statsmodels,
    matplotlib, catboost, imlearn

# Overview
## Key Findings
* The following features are associated with the following price segments:
![alt text](https://github.com/monacosc1/smartphone-models/blob/master/images/mode_table.png)

### Price and Whether a Model has 5G
* Higher prices and the presence of 5G are features associated with higher ratings
![alt text](https://github.com/monacosc1/smartphone-models/blob/master/images/graph_pair_1.png) 

### Details of Primary Camera
* Higher camera quality are associated with higher ratings.
![alt text](https://github.com/monacosc1/smartphone-models/blob/master/images/graph_pair_6.png) 

## Model Coefficients
* The final classification model had a validation accuracy of 85%. Confusion Matrix below:
![alt text](https://github.com/monacosc1/smartphone-models/blob/master/images/confusion_matrix.png) 

