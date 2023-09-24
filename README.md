A dataset of ~ 25K images (each of size 150 x 150) is taken.
Each image has a label from the following 6 categories: {'buildings': 0, 'forest': 1, 'glacier': 2, 'mountain': 3, 'sea' : 4, 'street': 5}.
The images are divided into 3 subsets: TRAIN (folder: seg_train): ~14K, VALIDATION (folder: seg_test): ~3K, PREDICTION (folder: seg_pred): ~7K.
* First, we used a fully-connected feed-forward neural network with H hidden layers (each containing N neurons) to classify the dataset. Then the validation set is used to determine the number of epochs for early stopping. The accuracy of the PREDICTION set is also determined.
* Now, we used a Convolutional Neural Network to perform the same task as described above.
