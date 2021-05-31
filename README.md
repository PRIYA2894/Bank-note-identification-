# Bank-note-identification-
### We will use the Banknote Dataset that involves predicting whether a given banknote is authentic given several measures taken from a photograph. It is a binary (2-class) classification problem. There are 1,372 observations with 4 input variables and 1 output variable.
### Let us divide the data into a training set and test set. This can be accomplished using sklearn train_test_split() function. 20% of data is selected for test and 80% for train
### Standardize the data using standard scaler. To make all the data have a similar mean, that is, a zero mean and a unit variance across the data, we shall apply the standard scalar algorithm in scikit library.
### Neural network layer is built using sequential model with one hidden layer having 15 neurons , activation= relu and kernel initializer= normal. In ouput layer we will take 1 neuron with activation sigmoid as it is binary classification problem.
### Loss function is binary cross entropy and optimizer is adam that’s why no need to give learning rate manually and epoch=250
