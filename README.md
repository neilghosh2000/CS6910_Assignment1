The description of the different files in the repository are as follows:

1) Firstly, we have used the train.py and train_augment.py to perform the sweep.
2) train_augment.py is rejected since the validation accuracy decreased.
3) The sweep.yaml has the code to initialize the sweep with the required hyperparameters.
4) CS6910_Assignment_1.ipynb is the final run with the best hyperparameters. It has results on the test data and the confusion matrix plots.
5) weights.pickle has the weights of the best model stored in it.
6) mnist.py has the model run on the three best set of parameters on the mnist dataset.
7) Sample Images.png has the one sample image from each of the 10 classes.

Best possible set of hyperparameters found on fashion-mnist dataset- 

Activation - ReLU,
Learning rate (eta) - 0.001,
L2 regularization (alpha) - 0,
Epochs - 10,
Hidden Layer Size - 128,
No. of layers - 4,
Optimizer - nadam,
Weight Initialization - Random,
Loss Function - Cross Entropy

Best Results - 

Training Accuracy - 0.9124,
Train Loss - 0.2366,
Validation Accuracy - 0.8978,
Validation Loss - 0.3064
