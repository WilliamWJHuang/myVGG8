# VGG8
This model is based on the original VGG model with some modifications.
I used the cifar-10 dataset to train and test the model. Cifar-10 consists of 60000 32x32 colour images in 10 classes and there are 50000 images in the training set and 10000 for the test set. The model includes 8 convolutional layers with batch normalization and 3 fully-connected layers. The model is trained on the Nvidia Tesla K80 GPU.

The model's accuracy on the cifar-10 test set is 0.90. For future works, there are some overfitting issues, it could be improved through hyper-parameter tuning or minor modifications of the model structure. Based on other papers, VGG strucure could reach around 93% accuarcy on the test set for the cifar-10 dataset. 
