# Project Name
> Outline a brief description of your project.
Multi-class classification model using a custom Convolutional Neural Network in TensorFlow: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

This is a multi-class classification model using a custom Convolutional Neural Network in TensorFlow. It is a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

It is a great advantage for the dermitologists and patients to be able to detect the possibility of cancer and cancer itself at the early stages. It improves the health care provided to the patient. 

Dataset used: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)

## Conclusions
- First model created based on data had high accuracy on training data but low on the validation data due to overfitting. 
- This overfitting was resolved by data augmentation. In the subsequent model, Validation accuracy improved but training model accuracy declined. Class imbalace caused this issue.
- Class imbalance issue was resolved by adding python package Augmentor. It improved overall accuracy of training data as well as validation data. Skin cancer can now be detected with rasonable accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

 - python
 - pathlib
 - tensorflow
 - matplotlib
 - numpy
 - pandas
 - os
 - PIL
 - keras


## Acknowledgements
This project is an assigment by Upgrad and IIIT-B as a part of Convolutional Neural Network in TensorFlow

## Contact
Created by [@onlyforneeraj] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
This project is open source and available for everyone to use as they wish.

<!-- You don't have to include all sections - just the one's relevant to your project --
