# Predict Future Sales	

1C COMPANY which was founded in 1991 specializes in the development, distribution, publishing, and support of mass-market software. Its products are being sold worldwide and sales are growing continuously. In this project, we are going to forecast the total sales for every product and store in the next month based on the given time-series dataset.

The key idea behind this problem is that we are supposed to implement Feature Engineering, by which we will discover the significant features that contribute a lot to sales.

### Data

Please refer to [Kaggle Link](https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales/data)

### Methods

Random Forest Regressor: A random forest is a meta estimator that fits a number of decision tree regressors on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting [1].

LightGBM: A gradient boosting framework that uses tree based learning algorithms. Please refer to this [link](https://github.com/microsoft/LightGBM) for more information.

### EDA 

See the file `EDA.ipynb`.

### Feature Engineering, Model Training and Evaluation

See the file `MODEL.ipynb`



### Reference

[1] scikit-learn documentation: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
