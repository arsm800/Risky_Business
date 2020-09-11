# risky_business

## Resampling

Of the four resampling techniques--Naive Random Oversampling, SMOTE 
Oversampling, Cluster Centroids Undersampling, and SMOTEENN Combination
(Over and Under) Sampling--when used with a logistic regression, SMOTEENN gives
us the highest balanced accuracy score at 0.658.  SMOTE oversampleing came in 
just behind at 0.646.  Naive Random Oversampling scored at 0.58.  Lastly,
Cluster Centroids came in at 0.531.  Overall, SMOTEENN and SMOTE appear to be
the strongest models.

When is comes to recall, SMOTEENN scores the highest at 0.64.  SMOTE comes in
second at 0.56, Cluster Centroids scored 0.52, and Naive Random Oversampling 
came in last at 0.47.  In the context of lending and credit and determine 
high-risk loans, a false negative is probably far more costly than a false 
positive.

SMOTEENN also has the highest geometric mean: 0.66.  SMOTE is just behind at 
0.64, while Naïve Random Oversampling is 0.57 and Cluster Centroids is 0.53.  
Since it scores the highest relative to the other sampling techniques, 
SMOTEENN appears to be the strongest model.

## Ensemble Learning

This exercise also utilized two ensemble classifiers algorithms on the same 
loan data set--the Balanced Random Forest Classifier and the Easy Ensemble
Classifier.  

For balanced accuracy (0.908 to 0.772), recall (0.88 to 0.66), and geometric 
mean (0.91 to 0.76), the Easy Ensemble Classifier scores higher.  From the 
Balanced Random Forest Classifier, the top features are 'total_rec_prncp' 
(0.078), 'total_pymnt_inv' (0.0673), and 'total_pymnt' (0.0616).

Generally speaking, the ensemple classifiers scored better than the resampling
algorithms.  The Easy Ensemble Classifier scored the highest of all alogorithms
tested.  For this particular data, classification seems to be a better model
algorithm than regression.


