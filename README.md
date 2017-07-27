# Machine-Learning-Assignment

    1.Initial data provide is processed and predictors with null values and NAs were removed. 
    Similar predictors in test data were also removed.
    
    2.Predictors which doesnot have any significance in the prediction such as "Time Stamp", "ID NO", " Name" etc were dropped from the data

    3.20% test data set is seperated to evaluate the model built using Random forests

    4.Random forests model is selected because of its advantages such as feature selection, 
    resistence to over fitting and ability to handle mulitcollinearity
    
    5.Random forests model is built using 500 trees and "m" (number of random predictors at each split) of 15
    The resultant confusion matrix using the seperated 20% test data is shown below.

    The classification of the 20 test instances are as follows
    ## Confusion Matrix and Statistics
 
           Reference
 Prediction    A    B    C    D    E
          A 1115    4    0    0    0
          B    0  753    2    0    0
          C    0    2  682    2    0
          D    0    0    0  640    3
          E    1    0    0    1  718
 
 Overall Statistics
                                           
                Accuracy : 0.9962          
                  95% CI : (0.9937, 0.9979)
     No Information Rate : 0.2845          
     P-Value [Acc &gt; NIR] : &lt; 2.2e-16       
                                           
                   Kappa : 0.9952          
  Mcnemar's Test P-Value : NA              
 
 Statistics by Class:
 
                      Class: A Class: B Class: C Class: D Class: E
 Sensitivity            0.9991   0.9921   0.9971   0.9953   0.9958
 Specificity            0.9986   0.9994   0.9988   0.9991   0.9994
 Pos Pred Value         0.9964   0.9974   0.9942   0.9953   0.9972
 Neg Pred Value         0.9996   0.9981   0.9994   0.9991   0.9991
 Prevalence             0.2845   0.1935   0.1744   0.1639   0.1838
 Detection Rate         0.2842   0.1919   0.1738   0.1631   0.1830
 Detection Prevalence   0.2852   0.1925   0.1749   0.1639   0.1835
 Balanced Accuracy 0.9988 0.9957 0.9979 0.9972 0.9976


