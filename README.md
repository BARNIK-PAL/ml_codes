A dataset of ~ 25K images (each of size 150 x 150) is taken.
Each image has a label from the following 6 categories: {'buildings': 0, 'forest': 1, 'glacier': 2, 'mountain': 3, 'sea' : 4, 'street': 5}.
The images are divided into 3 subsets: TRAIN (folder: seg_train): ~14K, VALIDATION (folder: seg_test): ~3K, PREDICTION (folder: seg_pred): ~7K.
* First, we designed a fully-connected feed-forward neural network with H hidden layers (each containing N neurons) to classify the dataset. Then the validation set is used to determine the number of epochs for early stopping. The accuracy of the PREDICTION set is also determined.
* Next, we designed a Convolutional Neural Network to perform the same task as described above.
* A review on **GloVe: Global Vectors for word representation** is based on the [paper](http://dx.doi.org/10.3115/v1/D14-1162) of the same title.
