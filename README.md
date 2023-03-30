# Devanagari-Handwritten-Character-Recognition
Optical Character Recognition using Convolutional Neural Network
Overview: 

The data of about 92,000 is imported. There are 46 classes and each class has 1700 images in it.

Preprocessing of data is performed using ImageDataGenerator module. It tilt, rotate, rescale the image and transform the images. Here, images are transformed to 32*32 size and batch size is 256, so 256 images will go through network before the weights are updated.

Defined the architecture of the model- There are 4 convolutional layers, 2 maxpooling layers, 1 dense layer, and output layer. Relu activation function is used for all layers except for output layer. Softmax actiivation function is used for output layer as it is multiclass classification.

At last the graphical user inteface is created by using tkinter library which will give prediction for single image.
