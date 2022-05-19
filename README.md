# Sign Language Classification using Resnet-50
bunnysaini/Sign-Language-Classification

## Abstract
Sign Language is an integral part of the lives of the deaf, mute, and hard of hearing (HOH). However, there exists a very slim number of people who can readily understand and translate the gestures and signs of Sign Language for them. The project aims to translate Indian Sign Language (ISL) into text by employing deep learning techniques such as Convolutional Neural Networks (CNN) to help the deaf and mute communicate with ease. 

## Dataset
We are using static images for our model to detect signs from the Indian Sign Language. We have used our own dataset that we have made by clicking pictures of the various signs in different lighting, backgrounds, and positions. It contains over 10,400 images containing 400 images for each letter of the English alphabet in Indian Sign Language.
![test_images](https://user-images.githubusercontent.com/83510385/169309912-01465560-064e-4901-81ca-ed537ee0bdee.png)
Out of the 10K images captured, ~8330 images are used for training and the rest for testing. This forms a roughly 4:1 split. which is sufficient for this medium-scale dataset. To get higher variation for our model to learn, we have captured the photos in different backgrounds, shadows and angles.

## Libraries/Software Used
-Jupyter Notebook
-  Python
- Keras
- Tensorflow
- Matplotlib

## Model Results
![acc_resnet](https://user-images.githubusercontent.com/83510385/169311479-162fa9b6-d0f8-43cf-b68a-7f8fb3968ca9.png)
