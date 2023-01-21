# CreditCardFraudDetection

A classifier model using XGBoost Classifier to figure out whether the transaction is valid or fraud, achieved an accuracy above 99%. 
Worked on –
1. EDA - Deleted and Created new features to improve accuracy. 
  Initial features : type, nameOrig, nameDest, Amount, oldbalanceOrig, newbalanceOrig, oldbalanceDest, newbalanceDest, isFraud, isFlaggedFraud.
  After Analysis: amount, oldbalanceOrg,	newbalanceOrig,	oldbalanceDest,	newbalanceDest,	isFraud,	type_OTHER,	type_TRANSFER,	errorbalanceOrg,	errorbalanceDest,	HourOfTheDay
2. Different models like Decision Trees, Random Forrest, XGBoost and AdaBoost. 
3. Various Performance metrics like confusion matrix, ROC curve, log loss to evaluate the model


Download dataset from https://www.kaggle.com/datasets/ealaxi/paysim1
