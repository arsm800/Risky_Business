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

SMOTEEENN also has the highest geometric mean: 0.66.  SMOTE is just behind at 
0.64, while Naïve Random Oversampling is 0.57 and Cluster Centroids is 0.53.  
Since it scores the highest relative to the other sampling techniques, 
SMOTEENN appears to be the strongest model.

## Ensemble Learning




