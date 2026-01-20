# Data-Science-Assignment-1-
# Introduction
Imbalanced datasets are a common challenge in real-world machine learning problems, especially in domains such as fraud detection. In such datasets, the minority class is significantly underrepresented, leading to biased models and poor predictive performance.
This assignment focuses on applying different sampling techniques to balance an imbalanced credit card dataset and analyzing their impact on the accuracy of multiple machine learning models.

# Objective
* To convert a highly imbalanced dataset into a balanced dataset
* To apply multiple sampling techniques
* To train and evaluate different machine learning models
* To identify which sampling technique performs best for each model

  
# Dataset Description
* Dataset: Credit Card Transaction Dataset
* Problem Type: Binary Classification
* Challenge: Severe class imbalance (fraud vs non-fraud transactions)

Before modeling, the dataset is transformed into a balanced class dataset using appropriate sampling techniques.


# Methodology
The methodology followed in this assignment is summarized below:

## Data Preprocessing
* Loaded the dataset using Pandas
* Checked for data distribution
* Separated features and target variable

## Handling Class Imbalance
* Identified imbalance in the target classes
* Converted the dataset into a balanced dataset using resampling techniques

## Sample Creation
* Created five different samples from the balanced dataset
* Each sample represents a unique data distribution

## Sampling Techniques Applied
Five different sampling techniques were applied:
* Sampling1
* Sampling2
* Sampling3
* Sampling4
* Sampling5

Each sampling technique was applied to a different sample.

## Model Training
Five machine learning models were trained:
* M1: Model 1
* M2: Model 2
* M3: Model 3
* M4: Model 4
* M5: Model 5

Each model was trained using one sampling technique at a time.

## Model Evaluation
* Models were evaluated using accuracy as the performance metric
* Results were recorded and compared

# Results Table
The table below shows the accuracy (%) obtained by each model using different sampling techniques:

| Model | Sampling1 | Sampling2 | Sampling3 | Sampling4 | Sampling5 |
|-------|-----------|-----------|-----------|-----------|-----------|
| M1    | 0.0       | 50.0      | 100.0     | 100.0     | 66.67     |
| M2    | 0.0       | 100.0     | 66.67     | 0.0       | 66.67     |
| M3    | 0.0       | 50.0      | 66.67     | 100.0     | 66.67     |
| M4    | 33.33     | 50.0      | 100.0     | 100.0     | 66.67     |
| M5    | 0.0       | 50.0      | 66.67     | 100.0     | 100.0     |
