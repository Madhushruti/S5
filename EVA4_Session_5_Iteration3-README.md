# S5
Assignment S5

#Goal	

Now we have model skeleton ready with 'not so' overfitting performance. The next focus is on reducing the number of Kernels as we are currently using way too many resources than needed for the problem in hand.

It makes sense to optimize the resources before we go ahead and optimize the model.

#Params	

9,186

#Best Train Accuracy	

99.34%

#Best Test Accuracy	

99.07%

#Observation/ Analysis/Conclusion	

The Model is not great because it's unable to reach close to the Target of 99.4%.
But I would continue to further optimize this model because -
The Model clearly is overfitting on all the epochs.
But the Accuracy difference is consistent.

A consistent model not meeting Target is better than an incosistent model meeting target.

Such a model can be trained further using different methods to overcome the overfitting Problem.

Hence in next step we shall try applying Batch Normalization to try how that impacts the model accuracy and consistancy across differnet Epochs.


#Comment	

We will continue to optimize the model further.
