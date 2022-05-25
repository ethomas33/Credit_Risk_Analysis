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

- In all of these models the recall for high risk loans is very low indicating they do not predict many. Conversely the low risk loans have a very high recall meaning the model does predicts far more correctly. 

- The combined performed the best on recall with 71% on high risk loans. Oversampling did the best on low risk loans at 68%.

- The f1-score which combines the two previously mentioned statistics indicate none of the models are very good with high risk loans. SMOTE Oversampling has the best f1 score for low risk loans.


## Summary: 

In summary if I was to pick one of the models I would use SMOTE Oversampling because it seems to have the best balance overall. I would however make clear that with these results human hands would still need to be involved in the process due to the lower values present in the statistics.