The description of the different files in the repository are as follows:

1) Firstly, we have used the train.py and train_augment.py to perform the sweep.
2) train_augment.py is rejected since the validation accuracy decreased.
3) The sweep.yaml has the code to initialize the sweep with the required hyperparameters.
4) CS6910_Assignment_1.ipynb is the final run with the best hyperparameters. It has results on the test data and the confusion matrix plots.
5) weights.pickle has the weights of the best model stored in it.