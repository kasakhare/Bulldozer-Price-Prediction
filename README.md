# Bulldozer-Price-Prediction

## 1. Problem defination

Predict the future sale price of bulldozers using given characteristics in dataset.

## 2. Data 

Kaggle:
https://www.kaggle.com/c/bluebook-for-bulldozers/data

The data is split into three parts:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition


## 3. Evaluation

The evaluation metric for this competition is the RMSLE(root mean squared log error) between the actual and predicted auction prices.

For more information:
https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation


## 4. Features

The key fields are in train.csv are:

* SalesID: the uniue identifier of the sale
* MachineID: the unique identifier of a machine.  A machine can be sold multiple times
* saleprice: what the machine sold for at auction (only provided in train.csv)
* saledate: the date of the sale
