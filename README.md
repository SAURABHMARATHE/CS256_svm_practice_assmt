# CS256_svm_practice_assmt
In this assignement I have learnt to use scikit SVM classifier to predict the affinity of a given chemical milecule againsta particular given protein BRAF-V600E.

Our goal was first to use test data on the given model. Initially we have used only the 20% of train data for the cross-validation purpose. (This change is at line 270 in the module)

Also, we were supposed to tweak the values of GAMMA to see the effect on accuracy. Currently I am using GAMMA=0.00001, and we are getting average accuracy for cross validation as 81 %.
Accuracy for test data is 66.66%, i.e. approximately 67%. (change at line 228)

Also, we were supposed to find the minimum value percentage of training dataset that could be used to train the model with good accuracy. Right now, I find that using 0.1 or 10% of the training data for the cross-validation purpose is good as it is less than 20% and gives same result.(change at line 216)

Pls note I am just printing the accuracy result and prediction result for test data, and not the support vector values, because we dont need that while running our model on test data.
