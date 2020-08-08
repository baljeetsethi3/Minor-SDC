This module focuses on detecting various objects from the scene i.e., scene parsing required to give the machine a vision of the things it is surrounded with. Scene parsing is required to give the machine visual perception for the environment, using Convolutional Neural Networks, to find the most optimal and legal path.

The model will be trained on a specific dataset which gives it object detection functionality for roads, and after a few milliseconds the model will be able to predict the object localization giving different masks to different types of objects.

The architectures used in this module include the FC-DenseNet56, as well as PSP-Net. The FC-DenseNet models 56,67,103 differs in only the numbers of layers, and used due to the parameter efficiency, a greater number of layers, and a good loss function. However, the PSP-Net model has been used due to its improved results and pyramid pooling approach.

## Semantic Segmentation
Semantic Segmentation is responsible for the mapping of each pixel corresponding to its class. Various algorithms and architectures exist to segment the image. We have been using the concept of Convolutional Neural Network. FC-DenseNet, PSPNet are the architectures proposed for the model.

## Hyperparameter Tuning
Hyperparameters play a crucial role in optimizing the code in terms of training, computation-wise and memory-wise. So, there is a need to have a hands-on-knowledge on hyperparameter tuning like batch-size, learning rate, number of epochs etc.


