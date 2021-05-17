# Decision-Tree-implementation
There are 2 projects under this repository.
One is a the classification of flower species of the very famous Iris dataset using Decision trees.
Another one is the classification of Wine quality using the same algorithm.
The procedure for both is similar.After fitting the models into a Decision tree classifier,performed Hyperparameter tuning to increase model accuarcy by finding out the best parameters.
The iris dataset showed no improvement post tuning .So our model is fine with an accuracy of 95%.
In the wine quality dataset, initially the test dataset was showing an accuracy of 62% and we didn't perform any pruning then. After tuning the various parameters  and post-pruning the branches, we found out
that the accuracy decreased to 57% .This shows that previously our model was probably overfitting  on the test-set and after tuning the model and pruning the branches, we get a more robust model which is completely fine and more generalised.
