# Deep Learning based American Sign Language Recognition

Final Deep Learning Project for USC EE-541 (A Computational Introduction to Deep Learning)

## Background

Sign language is a prominent form of communication for deaf communities across the world. However, there is a limited number of people outside of these communities who understand sign language. Therefore, there exists a need for a translation mechanism to convert sign language into a form that can readily understood by the general public. Furthermore, the nature of the sign language used is dependent upon region and, as such, no universal sign language exists. In the United States, American Sign Language (ASL) is the most widely used form and generally uses individual hand signs to convey full words. Fingerspelling is used in cases for which a sign for a word does not exist by signing individual letters.

## Objective

This project aims to develop a Deep Learning model to translate sign language to a text-based representation where the scope of the input is limited to the ASL alphabet used in fingerspelling. Specifically, when given a single image containing a hand sign, the model should classify the image according the ASL alphabet with a high degree of accuracy.

## Dataset

The dataset (training & testing combined) is 1.03 GB. It consists of 87,209 images (training & testing combined) in jpeg format. Each image is in RGB (Red-Green-Blue) scale and its dimensions are 200x200 pixels. The dataset folder has two sub-directories, namely the training dataset and the testing dataset. The training dataset contains one sub-folder for each of the 29 classes. The 29 classes are the 26 English alphabet characters (’a’ through ’z’), space, delete, and nothing. There are 3000 training images for each class. The testing dataset consists of 29 images (i.e., one image for each class). Additionally, the testing dataset will contain a number real-world images captured during the testing phase of the model. The dimensions of these real-world images will be scaled down to 200X200 pixels.

The dataset can be accessed [here](https://www.kaggle.com/datasets/grassknoted/asl-alphabet).
