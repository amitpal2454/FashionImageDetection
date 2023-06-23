# FashionImageDetection
Multiclass classification of Fashion Images


In this project, you will use convolutional neural networks to classify 28-by-28 grayscale images into 10 categories. The Fashion-MNIST data set is already separated into 60,000 training images and a 10,000 testing images.

The ten categories are:
T-shirt/top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle boot
 

There are multiple ways to approach this problem. You could perform transfer learning from a pretrained network like GoogleNet. Since the images are small, it may make more sense to train a new network from scratch where you can have more control over the input size. The best way to find a solution is to try both!

In this project, you will
View example images in the data set
Modify GoogLeNet for transfer learning and retrain the network
Train a network from scratch using an architecture from the documentation
Try different training options to improve the accuracy of the network
Test the network with real-world images
