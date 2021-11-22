# Credit Risk

## Overview
We are running an analysis for LendingClub needs to predict the credit card risk for futures leads and . 

## Results
- Oversampling
Balanced accuracy 67%, precision 1%, recall 70%, F1 is 2%

![Alt Text](https://github.com/CarlosRello/Credit_Risk_Analysis/blob/main/images/Oversampling.png)

- SMOTE Oversampling
Balanced accuracy 66%, precision 1%, recall 63%, F1 is 2%

![Alt Text](https://github.com/CarlosRello/Credit_Risk_Analysis/blob/main/images/SMOTE.png)

- Undersampling
Balanced accuracy 64%, precision 1%, recall 72%, F1 2%
![Alt Text](https://github.com/CarlosRello/Credit_Risk_Analysis/blob/main/images/Undersampling.png)

- Combination (Over and Under) Sampling
SMOTEENN sampling
Balanced accuracy 64%, precision 1%, recall 72%, F1 2%
![Alt Text](https://github.com/CarlosRello/Credit_Risk_Analysis/blob/main/images/Combination.png)

- Ensemble Learners
Balanced Random Forest Classifier
Balanced accuracy 79%, precision 3%, recall 70%, F1 6%
![Alt Text](https://github.com/CarlosRello/Credit_Risk_Analysis/blob/main/images/RandomF.png)

Easy Ensemble AdaBoost
Balanced accuracy 93%, precision 9%, recall 92%, F1 16%
![Alt Text](https://github.com/CarlosRello/Credit_Risk_Analysis/blob/main/images/Easy.png)

## Conclusion
Easy Ada is the most accurate model
