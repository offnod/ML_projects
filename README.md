Project03: IMDB and Neteflix classifier

Goal: Binary classifier practice using IMDB dataset profiling most popular Netflix titles. Dataset is mostly categorical of bool values and I was curious about what kind of performance such a dataset would achieve with such sparse information. Evaluated and optimized Random Forest Classifier parameters and performance measures. Data is inherently highly biased due to targeting smaller data subset (thousands of rows, tens of features) to reduce code execution time, motivated by hardware limitations.

Outcome: IMDB dataset features are poor indicators of Netflix catalog. PCA used to identify features to exclude even further, did not perform significantly better. Achieved greater understanding of the process to evaluate performance measures and parameters using grid search. Achieved greater understanding of benefits in organizing classes, functions, and parameters.

Next steps: Tackle a larger dataset that intuitively should contain more features with stronger correlation in order to motivate value in spending more time evaluating multiple training models and tuning models. Possibly attempt increasing complexity of training model, although still motivated by hardware limitations.
