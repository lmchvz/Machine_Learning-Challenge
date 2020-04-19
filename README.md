# Machine Learning Challenge - Exoplanet Exploration

I've compared the Random Forest Model with the SVC as they are both classification models and we are trying to classify the exoplanets. Both models performance increased after using the GridSearch function. We can conlcude that the Random Classification Model performed better after reviewing the model's scores listed below.  

## Random Forest Model Performance: 

### Initial Scores: 
Training Data Score: 0.9938966240701889
Testing Data Score: 0.8752860411899314

### After using GridSearch's best params: 
New Training Data Score: 1.0
New Testing Data Score: 0.898741418764302

### Classification Report: 
                 precision    recall  f1-score   support

     CANDIDATE       0.83      0.75      0.79       411
     CONFIRMED       0.83      0.86      0.84       484
FALSE POSITIVE       0.97      0.99      0.98       853

      accuracy                           0.90      1748
     macro avg       0.88      0.87      0.87      1748
  weighted avg       0.90      0.90      0.90      1748

## SVC Model Performance: 

### Initial Scores: 
Training Data Score: 0.8455082967766546
Testing Data Score: 0.8415331807780321

### After using GridSearch's best params: 
New Training Data Score: 0.8865153538050734
New Testing Data Score: 0.8792906178489702


### Classification Report: 
                 precision    recall  f1-score   support

     CANDIDATE       0.81      0.67      0.73       411
     CONFIRMED       0.76      0.85      0.80       484
FALSE POSITIVE       0.98      1.00      0.99       853

      accuracy                           0.88      1748
     macro avg       0.85      0.84      0.84      1748
  weighted avg       0.88      0.88      0.88      1748


