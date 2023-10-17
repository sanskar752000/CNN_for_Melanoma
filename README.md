# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Multiclass classification model using a custom convolutional neural network in TensorFlow
- Built a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. Found that there was an data imbalance in the dataset before running my final model.
2. Data imbalance is fixed using Augmentor by creating 500 samples for each class.
3. After doing some changes in the CNN architechture by adding dropout layers and batch normalisation layer, the overfitting of the model is gone and the accuracy
for the training and validation is 82.15 and 71.49 respectively
4. As per the final model training and validation accuracy have been increased.
5. Class rebalance certainly did helped in augmentation and achieving better accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Numpy
- Tensorflow
- keras
- pandas
- matplotlib
- seaborn
- anaconda
- colab
- vscode


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was as case study provided by UpGrad
- References taken:
- Google, Kaggle, Medium, towardsdatascience


## Contact
Created by [https://github.com/sanskar752000] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->