# Credit_Risk_Analysis

## Overview of the Analysis
This analysis is done to assess credit risk of applicants using machine learning. Several different machine learning techniques are applied , then the models are assessed to choose the best technique that applies to this type of problem.

## Results: 
1.Random oversampler
![](https://github.com/mdabbous88/Credit_Risk_Analysis/blob/main/Random%20oversampler.png)

-The balanced accuracy score for the random oversampler is 0.65, which tells that the model has predict 65% of the test sample correctly. 

-The model has very low precision (close to 0) in detecting a high risk, and a very high precision in detecting low risk applicants(100%).

-The model has moderate sensitivity (0.63) in detecting a high risk, and a moderate sensitivity (0.67) in detecting low risk applicants.


2.SMOTE oversampling
![](https://github.com/mdabbous88/Credit_Risk_Analysis/blob/main/SMOTE.png)

-The balanced accuracy score for the random oversampler is 0.64, which tells that the model has predict 64% of the test sample correctly. 

-The model has very low precision (close to 0) in detecting a high risk, and a very high precision in detecting low risk applicants (100%).

-The model has moderate sensitivity (0.61) in detecting a high risk, and a moderate sensitivity (0.67) in detecting low risk applicants.


3.Undersampling
![](https://github.com/mdabbous88/Credit_Risk_Analysis/blob/main/undersampling.png)

-The balanced accuracy score for the random oversampler is 0.51, which tells that the model has predict 51% of the test sample correctly. 

-The model has very low precision (close to 0) in detecting a high risk, and a very high precision in detecting low risk applicants(100%).

-The model has moderate sensitivity (0.59) in detecting a high risk, and a moderate sensitivity (0.44) in detecting low risk applicants.


4.SMOTEENN
![](https://github.com/mdabbous88/Credit_Risk_Analysis/blob/main/SMOTEEN.png)

-The balanced accuracy score for the random oversampler is 0.64, which tells that the model has predict 64% of the test sample correctly. 

-The model has very low precision (close to 0) in detecting a high risk, and a very high precision in detecting low risk applicants(100%).

-The model has moderate sensitivity (0.70) in detecting a high risk, and a moderate sensitivity (0.58) in detecting low risk applicants.


5.Balanced Random Forest Classifier

![](https://github.com/mdabbous88/Credit_Risk_Analysis/blob/main/Balanced%20Random%20Forest%20Classifier.png)

-The balanced accuracy score for the random oversampler is 0.79, which tells that the model has predict 79% of the test sample correctly. 

-The model has very low precision (close to 0) in detecting a high risk, and a very high precision in detecting low risk applicants(100%).

-The model has moderate sensitivity (0.70) in detecting a high risk, and a high sensitivity (0.89) in detecting low risk applicants.

6.Easy Ensemble Classifier

![](https://github.com/mdabbous88/Credit_Risk_Analysis/blob/main/Easy%20ensemble.png)

-The balanced accuracy score for the random oversampler is 0.92, which tells that the model has predict 92% of the test sample correctly. 

-The model has very low precision (close to 0) in detecting a high risk, and a very high precision in detecting low risk applicants(100%).

-The model has high sensitivity (0.91) in detecting a high risk, and a high sensitivity (0.94) in detecting low risk applicants.



## Summary:
Since the business is to check the risk of the applicant, the most important aspect is if the model misses a high risk applicant and lables the applicant as low risk.

So, all the models reslts show moderate sensitivity in detecting high risk except for the EasyEnsembleClassifier model which has a very high sensitivity of 0.94 in detecting high risk applicants. Also, this models has a 92% balanced accuracy score which is a very good score in prediciting the risk.

