# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

This analysis is a machine learning program being used to identify if a loan application is high or low risk. 


## Results: 

#### Oversampling
![Oversampling](https://github.com/ethomas33/Credit_Risk_Analysis/blob/de18d7f61ff4f7075567037da2f0f03420193692/Challenge%20Images/Oversampling.PNG)

#### SMOTE Oversampling
![SMOTEOver](https://github.com/ethomas33/Credit_Risk_Analysis/blob/3e66c5714721a77329fee9065638b1d50bead657/Challenge%20Images/SMOTEOver.PNG)

#### Undersampling
![Undersampling](https://github.com/ethomas33/Credit_Risk_Analysis/blob/3e66c5714721a77329fee9065638b1d50bead657/Challenge%20Images/undersampling.PNG)


#### Combination (over and under) Sampling
![Combination](https://github.com/ethomas33/Credit_Risk_Analysis/blob/3e66c5714721a77329fee9065638b1d50bead657/Challenge%20Images/combination.PNG)


Each of these results contain scores for precision, recall and f1-score.

The recall means "how many of this class you find over the whole number of element of this class"

The precision will be "how many are correctly classified among that class"

The f1-score is the harmonic mean between precision & recall

The support is the number of occurence of the given class in your dataset (so you have 37.5K of class 0 and 37.5K of class 1, which is a really well balanced dataset.

The thing is, precision and recall is highly used for imbalanced dataset because in an highly imbalanced dataset, a 99% accuracy can be meaningless.


Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.