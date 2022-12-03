spectral data fusion and image classification


fuse_training can load data from two cameras, fuse them, then train a classifier, adding this training data to a csv file
this csv file can then be used in this code to run a classifier to predict fuels present in a spectral dataset

select_validation_data loads in and fuses a set of hyperspectral data from two cameras, then allows the user to select validation data interactively, in order to create a ground truth data set for testing the performance of the classifier created previously
