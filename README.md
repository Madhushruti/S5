# S5
Assignment S5
-----

#Goal	
We intend to tackle the Overfitting problem by including batch normalization in the model.

#Params	
9322

#WITH 20 EPOCHS
#Best Train Accuracy	
99.4%

#Best Test Accuracy	
99.24%
#Observation/ Analysis/Conclusion	

We used Batch Normalization in this Model to tackle the ovefitting issue.
This Model is GREAT. For all the Epochs (except for 2) the difference between Training and Test Accuracy is very small.
Why the model is good?
The model is very good  because of the CONSISTENCY in the Training and Test Accuracy difference.

#WITH 15 EPOCHS

#Best Train Accuracy	
99.68%

#Best Test Accuracy	
99.1%


#Observation/ Analysis/Conclusion	
The model does not reach the Target accuracy for almost all the EPOCHs.
The model is consistent for last few EPOCHS, i.e.the difference between Training and Test Accuracy is not large but still, hence even the Model suffers from Overfitting Problem , but it being consistent leads to conclusion that we could push the model further to learn better.
Next optimization technique we would use is Drop Out method.

Drop out helps to reduce the train and test accuracy gaps, hence we would give it a shot to verify if this method could help us to overcome Overfitting Problem in the Model


#Comment	
This means we must continue to train the model to achive better accuracy.
