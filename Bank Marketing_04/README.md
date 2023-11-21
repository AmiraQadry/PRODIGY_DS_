# Bank Marketing - Decision Tree Classifier

This project aims to build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. 
The classifier is trained using the Bank Marketing dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing).

## Dataset

The Bank Marketing dataset contains information about direct marketing campaigns (phone calls) of a Portuguese banking institution. 
The classification goal is to predict if the client will subscribe a term deposit.

- Dataset Characteristics: Multivariate
- Subject Area: Business
- Associated Tasks: Classification
- Feature Type: Categorical, Integer
- Number of Instances: 45211
- Number of Features: 16

The dataset is provided in several files:

1. `bank-additional-full.csv`: Contains all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010).
2. `bank-additional.csv`: Contains 10% of the examples (4119), randomly selected from `bank-additional-full.csv`, and 20 inputs.
3. `bank-full.csv`: Contains all examples and 17 inputs, ordered by date (older version of the dataset with fewer inputs).
4. `bank.csv`: Contains 10% of the examples and 17 inputs, randomly selected from `bank-full.csv` (older version of the dataset with fewer inputs).

## Prerequisites

Make sure you have the following dependencies installed:

- Python 
- Pandas 
- scikit-learn 

## Results

The decision tree classifier achieved an accuracy of 87% on the test set. The classification report provides detailed metrics for each class (positive and negative).
![image](https://github.com/AmiraQadry/PRODIGY_DS_/assets/106974489/6cf3f2a8-f888-434d-8add-3b71921acf45)
