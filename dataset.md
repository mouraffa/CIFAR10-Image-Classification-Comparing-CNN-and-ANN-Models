# CIFAR10 Dataset

The CIFAR10 dataset is a widely used benchmark dataset for image classification tasks. It consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The dataset is split into 50,000 training images and 10,000 test images.

The 10 classes in the CIFAR10 dataset are as follows:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

Each image in the dataset is a low-resolution color image with 32x32 pixels. The goal of the CIFAR10 dataset is to classify these images into the correct class category.

The CIFAR10 dataset is commonly used for evaluating and comparing different image classification algorithms and models. It provides a challenging task due to the small image size and the complexity of distinguishing between the 10 different classes.

## Usage in this Project

In this project, the CIFAR10 dataset is used for training and evaluating image classification models, specifically a Convolutional Neural Network (CNN) and an Artificial Neural Network (ANN). The models are trained on the CIFAR10 training set and evaluated on the CIFAR10 test set to measure their performance in classifying the images into the correct categories.

The CIFAR10 dataset is loaded using the TensorFlow Keras `datasets` module, and the images are preprocessed by normalizing the pixel values to a range of 0 to 1. The class labels are one-hot encoded for training the models.

The purpose of using the CIFAR10 dataset in this project is to compare the performance of the CNN and ANN models and understand the advantages of CNNs over ANNs for image classification tasks.

---

Feel free to modify the dataset.md file and add more information or details about the CIFAR10 dataset if needed.
