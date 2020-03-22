# Credit_risk_analysis

# Analysis

Below is detailed description of each resampling technique.
Let’s go over the results in the classification report:

Precision: Precision is the measure of how reliable a positive classification is. From our results, the precision for the good loan applications can be determined by the ratio TP/(TP + FP). The precision for the bad loan applications can be determined as follows: TN/(TN + FN). A low precision is indicative of a large number of false positives—of the Total loan applications we predicted to be bad applications, Avg TP were actually good loan applications.

Recall: Recall is the ability of the classifier to find all the positive samples. It can be determined by the ratio: TP/(TP + FN). A low recall is indicative of a large number of false negatives.

F1 score: F1 score is a weighted average of the true positive rate (recall) and precision, where the best score is 1.0 and the worst is 0.0.

Support: Support is the number of actual occurrences of the class in the specified dataset. For our results, there are X actual occurrences for the good loans and Y actual occurrences for bad loans.


Techniques	                              Avg precision   	 recall 	 f1-score  	 support   Balanced Accuracy
Naive Random Oversampling	                  0.99	            0.58	    0.73	      17205         0.66
SMOTE Oversampling	                        0.99	            0.67	    0.8	        17205         0.64
Undersampling	                              0.99	            0.4	      0.56      	17205         0.53
Combination (Over and Under) Sampling	      0.99	            0.57	    0.72	      17205         0.65

SMOTE Oversampling	 is the best sampling technique with  high recall rate of 0.67 which helps in finding best Loan application along with the 0.64 balanced accuracy or how often the classifier is correct. In addition it F1 score being highest with 0.8 that is close to 1. 

