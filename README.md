# Credit_Risk_Analysis

## **Overview of Analysis**
In this project, I used different ways of machine learing to analyze the credit card risk from a credit dataset imported from LendingClub. Data resampling was done using the methods of oversample, undersample and combination of over- and uner- sampling to determine the better way at predicting credit risk. Also different models of machine learning was applied. THe accuracy score, confusion matrix and classification report of each model are generated to compare the performance of tested model.

## **Results**

- Results from RandomOverSampler mehtod:

     ![random_oversampling_results](https://user-images.githubusercontent.com/90361056/149701086-f1538fb2-0c9c-4e31-b491-09eb61248feb.PNG)

- Results from ClusterCentroids undersampling mehtod:
     
     ![ClusterCentroids_undersampling_results](https://user-images.githubusercontent.com/90361056/149700758-0c3541a5-7af3-442b-b731-909ad3f5e921.PNG)

- Results from SMOTE oversampling mehtod:
 
     ![SMOTE_oversampling_results](https://user-images.githubusercontent.com/90361056/149701417-f1a5f2dc-d6da-4a79-bf02-1c24fa1f8a63.PNG)

- Results from SMOTEENN combined sampling mehtod:
 
    ![SMOTEENN_combinesampling_results](https://user-images.githubusercontent.com/90361056/149701775-8dd64a63-edec-4a87-a7d8-9f6b68092500.PNG)

- Results from BalancedRandomForest oversampling mehtod:

     ![balancedRandomForest_oversampling_results](https://user-images.githubusercontent.com/90361056/149690322-321bdd98-15ba-4d20-a5f2-9a55aae3493d.PNG)
     
- Results from EasyEnsembleClassfier mehtod:

     ![easyEnsembleClassifier_results](https://user-images.githubusercontent.com/90361056/149702424-08f19393-66a6-4caf-93d7-122ef5479919.PNG)


## **Summary**
In the first portion of analysis, I comapred resampled data using oversampling, undersampling and combination of over- and uner- sampling, and analyzed resampled data using four different of machine learing models (RandomOverSampler, ClusterCentroids undersampling, SMOTE oversampling, and SMOTEENN combined sampling). From the caclulated results, we can see the accuracy score of these four models are not very high, around 0.5 -0.7. And their recall numbe for high_rish is not very good either, in the range of 0.5-0.6, which means they are not sensitive to detect the fraudulant credit. In the second portion of analysis, I comapred BalancedRandomForest oversampling mehtod and EasyEnsembleClassfier mehtod. BalancedRandomForest oversampling mehtod did not increase performance on accuracy score and recall. But EasyEnsembleClassfier have a very high accuracy score (0.93) and the recall for high_rish and low_risk are high too (0.92 and 0.93, respectively). Therefore, the results show that EasyEnsembleClassfier is the best machine learning modle to predict the credit risk for this dataset.
     
