# Multivariate-Time-Series-Bi-Directional-LSTM
# Bidirectional LSTM: Time Series

## Problem
* There are two data sets, coming from a ADCP(Acoustic Doppler Current Profiler) device. ADCP devices are fitted with multiple sensors to record the direction, temerature, roll, pitch of under water current. 
* The training data has 11 variables, and 42668 observations.
* The first column or the first variable is the Target and other 10 are features. 
* In the evaluation data set has 7604 observations and same number of variables as the training set, but the first coulmn/variable is measured/recored incorrect.
* The task is to train a model from the first data set so that we can reproduce the incorrect variable (the first coulm in the evaluation set) 

* __The model trained on good dataset(train dataset) will predict the first column of the bad data set (evaluation set)__

* At the end, a statistical test is required to compare if the model has predicted correctly.

## Data Description

### Training Data

*  __Shape of Training Data: (42668, 11)__
![grafik.png](attachment:grafik.png)

### Evaluation Data
* __Shape of Training Data: (7604, 11)__
![grafik-2.png](attachment:grafik-2.png)

## 
