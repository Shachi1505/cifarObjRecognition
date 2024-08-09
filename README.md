# CIFAR Object Recognition Project
## Deep Learning Project

The CIFAR-10 dataset, created by the Canadian Institute For Advanced Research, is a widely utilized collection of images in the fields of machine learning and computer vision. It consists of 60,000 32x32 color images categorized into 10 distinct classes: airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks, with 6,000 images in each class. This dataset serves as a standard benchmark for training and evaluating machine learning models, particularly for object recognition tasks. Due to the low resolution of the images, researchers can efficiently test various algorithms and approaches, making CIFAR-10 a valuable resource in the development of computer vision techniques. It is taken from KAGGLE using an API.

Images are converted to numpyarray for processing. Built neural network model using libraries like **Keras and tensorflow** are designed to efficiently extract and learn features from images. They employ multiple filters in convolutional layers to detect patterns such as edges, textures, and shapes. *Layers like Dense, BatchNormalization and Flatten* integrate these learned features for classification tasks. **Adam optimization** algorithm for efficient gradient descent.


 **ResNet50** 
ResNet50, is a 50-layer deep network that has been pre-trained on large datasets like ImageNet. It is part of the Residual Networks (ResNet) family, which introduces "skip connections" or "residual connections" to allow the model to learn deeper representations without suffering from the vanishing gradient problem.
*Application:* It can be effectively applied to a CIFAR object recognition model to enhance accuracy. By leveraging its deep architecture and pre-trained layers, ResNet50 captures complex patterns in CIFAR images. Fine-tuning this model on CIFAR data allows for powerful feature extraction, improving performance in image classification tasks.

**Results**
Achieved an accuracy of 97%, (epochs=10)  An epoch refers to one complete pass of the entire training dataset through the learning algorithm. During each epoch, the model processes all training examples, updating its weights based on the error calculated.



