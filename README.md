# CIFAR10-img-classificaion-pytorch
In this notebook, I am going to classify the images of [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. This dataset consists of 10 classes of images, for example airplanes, dogs, cats and others. The images are preprocessed and then trained using a four types of neural nets on the training set. The images are normalized with the mean to zero and standard deviation to 1.

# Prerequesites
- Python 3.6+
- PyTorch 1.0+

# Abstract
- The CIFAR-10 dataset contains 60000 32x32 color images in 10 classes, 6000 images per class. There are 50000 training images and 10000 test images.

- The classes in the dataset:
    - Airplane
    - Automobile
    - Bird
    - Cat
    - Deer
    - Dog
    - Frog
    - Horse
    - Ship
    - Truck

- There is no overlap between the classes i.e. mutually exclusive classes.

# Tasks perfomed in the Notebook
- Loading the Data
- Understanding the dataset
- Normalizing the training dataset
- Model architecture and construction
- Traing the model (by using the implemented Trainer class)
- Prediction
