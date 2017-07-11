Predicting Titanic survival

based on parents aboard, siblings aboard, and place of embarkment

logregtitanic--logistic regression model
more preprocessing could improve model (e.g., encode age as child/adult/elderly; encode siblings as >0, >2, >4 since this is ordinal) 

decisiontree_titanic--decision tree model
less preprocessing is necessary
need to deal with NaN's in Age data (use the mean? seems like it would get noisy but maybe not as bad as deleting ~200 entries...)



