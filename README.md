# UK-Used-Car-Price-Prediction

**1. Introduction**

***Dataset***

The dataset was downloaded from Kaggle and contains information of more than 15K Volkswagen used cars that were sold in July 2020 in the UK.

***Objective***

The objective of this project is to build a model to predict the used car price for personal or professional interests, based on the most significant features selected in the dataset.

**2. Techniques**

The car price prediction requires the regression supervised machine learning techniques among which I select the linear regression algorithm to train our model.
During the training process, we will also check linear assumptions and evaluate the performance of the model.

Used libraries:

* pandas: data cleaning/transformation & data visualization
* statsmodels.api: modeling
* standardScaler: standardizing the dataset
* assumptions: built function to check linear assumptions of the model

**3. Outcomes**

After the training process, the model managed to predict the car price with an Adj R-squared of 90%.

Regarding linear assumption check, one assumption out of five is violated.

- validated assumptions: Linearity, Multicollinearity, Autocorrelation, Homoskedasticity of Error Terms,
- violated assumption: Normality

Explanation: The violation of normality assumption might be because there still are outliers even after dropping them twice. 

Solution: 
* Continue to handle outliers and remediate the violated normality, or
* Use other regression algorithms whose result is not impacted by the outliers such as Random forests, Decision Trees... 

