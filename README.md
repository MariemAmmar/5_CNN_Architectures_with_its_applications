# Overview of the whole notebook

The code snippets provided consist of the most well-known convolutional neural network (CNN) architectures implemented using the Keras library.

## LeNet-5

The first code part implements the LeNet CNN architecture, which is one of the earliest CNN models. 
One of the earliest successful CNN architectures developed in the 1990s by Yann LeCun for handwritten digit recognition. 
It consists of two sets of convolutional and pooling layers followed by three fully connected layers. 
The LeNet model is primarily used for digit recognition tasks.

![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/LeNet-5%20Architecture.PNG)
![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/LeNet-5%20Architecture%202.PNG)


## AlexNet: 
    
The second code part implements the AlexNet CNN architecture, which won the ImageNet Large Scale Visual Recognition Challenge in 2012.
It was the first deep CNN architecture that achieved state-of-the-art performance on the ImageNet dataset. 
It consists of five convolutional layers, three fully connected layers, and two dropout layers.

![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/AlexNet%20Architecture%202.PNG)
![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/AlexNet%20Architecture.PNG)



## VGG16 and VGG19: 
    
The third code part implements a CNN architecture using multiple VGG blocks. These CNN architectures were developed by the Visual Geometry Group at the University of Oxford in 2014. They are known for their simplicity and their success in the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) competition.
The VGG model consists of 16 to 19 layers, which are mainly composed of convolutional layers followed by max-pooling layers.

![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/VGG%20Architecture.PNG)
![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/VGG16%20VS%20VGG19.PNG)
![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/Variants%20VGG.PNG)



## Naive Inception/GoogLeNet and Inception-V3: 

The fourth code part implements a CNN architecture using a naive inception module and an inception V3 module.
It was developed by Google researchers in 2014, this architecture introduced the Inception module that allowed for more efficient computation and deeper networks. 
The inception module consists of multiple convolutional layers with different kernel sizes concatenated at the end.


![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/Inception%20Module%20Naive%20version.PNG)
![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/Inception%20module%20V3%20Archtecture.PNG)


## ResNet: 
The fourth code part implements the ResNet CNN architecture.
It was Developed by Microsoft researchers in 2015. 
ResNet (short for Residual Network) introduced the concept of skip connections to help overcome the problem of vanishing gradients in deep networks.

![alt text](https://raw.githubusercontent.com/MariemAmmar/The_most_well-known_CNN_Architectures_with_applying-image-classification/main/ResNet%20Architecture.PNG)


## Applying  Image Classification 
    
Each of these architectures has unique features. All these models have achieved high accuracy in our image classifcation task which is a computer vision task.
These architectures have played a significant role in advancing the field of computer vision and have been used as the basis for many subsequent architectures.

Note : We add for this application the use of other CNN architectures which are : 
        
* DenseNet: Developed by researchers at Facebook AI Research in 2016, DenseNet introduced the concept of dense blocks where every layer is connected to every other layer in a feed-forward manner. This architecture has shown to be highly efficient and effective in image classification tasks.

* EfficientNet: Developed by Google researchers in 2019, EfficientNet uses a novel compound scaling method to optimize the depth, width, and resolution of the network. It has achieved state-of-the-art performance on the ImageNet dataset while using fewer parameters and less computation than previous architectures.


 

