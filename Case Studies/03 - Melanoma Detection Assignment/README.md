# Project Name
> Melanoma Detection


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This is multiclass classification model using a custom convolutional neural network in TensorFlow.
- What is the business probem that your project is trying to solve?
  - To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the dataset that is being used?
  - Skin cancer ISIC The International Skin Imaging Collaboration: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In the first CNN model plot we see that training accuracy is around 88% and validation accuracy is around 57%. Both are are off by large margins. The difference in accuracy between training and validation accuracy is noticeable which a sign of overfitting
- Using Augmentation and Dropout layer in our next model has improved the model compared to previous one. Train and validation accuracy are inline.
- By Handling class imbalances model has further improved


## Technologies Used
- Python 
- Keras
- Tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- References
  - [https://github.com/nicknochnack/ImageClassification/blob/main/Getting%20Started.ipynb](https://github.com/nicknochnack/ImageClassification)
  - https://www.tensorflow.org/tutorials/images/classification


## Contact
Created by [@scpowar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
