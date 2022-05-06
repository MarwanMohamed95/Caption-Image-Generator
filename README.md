
# **Image Caption Generator** 

In this project I will implement image caption generator that takes an input image and generate a caption that describes the image.
- First we will extract the features from the images using Xception pre-trained model and encode the captions using Keras tokenizer class to train the model.
- in testing we will feed the model with the feature of the test image and a starting word to generate the second word and this process will repeat recursively to generate the full description caption.     
    # Steps of the project:
    --------------------------------
    1. Importing Required Libraries
    2. Retrieving the data (Images and Desctiption Captions)
    3. Defining the Pathes variables
    4. Preparing the images
    * 4.1. Defining the model
    * 4.2. Extracting the features from the images

    5. Preparing the Description Captions text
    * 5.1. Loading the captions of all images
    * 5.2. Creating the dictionary of images-captions pairs
    * 5.3. Cleaning the descriptions

    6. Preparing the training data (features and description captions)
    7. Tokenization
    * 7.1. Creating the training corpus
    * 7.2. Creaing the tokenizer object to map each word to number

    8. Preparing the validation data: (features and description)
    9. Creating the data generator
    10. Defining the model
    11. Testing the model on the testing images

## An overview of the Xception model
- Xception is a deep convolutional neural network architecture that involves Depthwise Separable Convolutions. Xception is also known as “extreme” version of an Inception module.

![cnn_model](https://github.com/MarwanMohamed95/Caption-Image-Generator/blob/main/Xception.png?raw=true)

## The Architecture of the final model:
![model](https://github.com/MarwanMohamed95/Caption-Image-Generator/blob/main/model.png?raw=true)

## Some of the results:
![r1](https://github.com/MarwanMohamed95/Caption-Image-Generator/blob/main/Result1.png?raw=true)

![r2](https://github.com/MarwanMohamed95/Caption-Image-Generator/blob/main/Result2.png?raw=true)

## 🛠 Skills
Deep Learning, Computer Vision, Python, tensorFlow, OpenCV...


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marwanabdelsalam95/)

