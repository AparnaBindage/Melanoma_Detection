# Project Name
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Information](#general-information)
* [Project Pipeline](#general-information)
* [Conclusions](#conclusions)
* [Libraries Used](#libraries-used)



## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Project Pipeline
- Data Reading/Data Understanding

- Dataset Creation
    - Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.

- Dataset visualisation 
    - Create a code to visualize one instance of all the nine classes present in the dataset 

- Model Building & training : 
    - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).

- Model Building & training on the augmented data :
    - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

- Class distribution: Examine the current class distribution in the training dataset 

    - Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
    - Model Building & training on the rectified class imbalance data :
        - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to   normalize pixel values between (0,1).


## Conclusions
- Convolutional neural networks helps to classify images accurately
- The model is able to classify disease with training accuracy of 89% and validation accuracy of 81%
- With the help of class imbalance treatment we are able to improve accuracy
- Overfitting is also reduced with data augmentation and class imbalance treatment
- Adding dropout layers also helps in reducing overfitting to some extent


## Libraries Used
- TensorFlow
- Keras
- Matplotlib
- Pandas
- Numpy
- Glob

## Contact
Created by AparnaBindage  - feel free to contact me!