# S5
Assignment S5


#Goal	
In this iteration we intend to increase Model Accuracy to 99.4% and beyond at the same time maintaining the model consistancy.

#Params	
9,923

#WITH 15 EPOCHS

#DropOut value
0.02

#Best Train Accuracy	
99.33%

#Best Test Accuracy	
99.4%

Learning Rate:
Used StepLR function from torch.optim.lr_scheduler Class, to manipulate the model in a way that - The model should multiply the learning 
rate by 0.1 after Epoch 6.

#Observation/ Analysis/Conclusion	

In this iteration the learning rate was altertered. The change in learning rate certainly helped to increase the Test Accuacy and enabled to 
reach target accuracy, but this is not the right way to manipulate Learning Rates.
In further iterations, we can implement systematic method to do so.

We have achived target accuracy also the Model did not fall to Ovefitting.
This is a decent model.
