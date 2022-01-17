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

     ![easyEnsembleClassifier_results](https://user-images.githubusercontent.com/90361056/149701514-77496119-76c8-4da9-a15c-41459c3b47f7.PNG)


## **Summary**
From data in results session, 52% of Vine reviews were 5 stars, and 58% of non-Vine reviews were 5 stars. We can see that the percentage of 5-star reviews for the two types of review (paid vs unpaid) is very close. Therefore, I don't think there is bias towards reviews that were written as part of the Vine program.
     
