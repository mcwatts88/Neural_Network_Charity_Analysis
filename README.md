# Neural Network Charity Analysis

## Overview

Utilizing deep neural networks to determine if charity funding from Alphabet Soup would help applicants

## Results

### Data Preprocessing

* The target is variable "IS_SUCCESSFUL"
* "The features for this model were "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS" and "ASK_AMT"
* Columns "EIN" and "NAME" were removed from the data

### Compiling, Training, and Evaluating the Model

* 2 hidden layers were used for the model. The first layer used "relu" activation and contained 30 neurons. The second layer used "sigmoid" activation to give a binary output and used 15 neurons.
* ~73% was the best the model achieved with a goal of 75%.
* Optimization attempts included more neurons for each layer, different activitions, and additional hidden layers

## Summary

Ultimately the goal of 75% accuracy could not be met. Utlizing the keras tuner tool might be a possible next step as it can optimize the model for you, or changing to an ensemble model to better fit the dataset.