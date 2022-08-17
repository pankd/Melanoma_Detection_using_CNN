# Melanoma Prediction using CNN
Problem statement:
The task in this assignment is to build a multiclass classification model using custom CNN with TensorFlow framework which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early and it accounts for around 75% of skin cancer deaths. CNN model can help to evaluate images and alert dermatologists about the presence of melanoma. This can speed up the diagnosis and reduce a lot of manual effort.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Dataset
  The dataset used for modelling consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images are sorted according to the classification taken with ISIC and the data has been grouped into 9 groups as below as per the disease type:

  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion

- The intent of this project is to come up with a CNN model that can predict Melanoma correctly and early detection of this anomaly can be done
  which can help save many lives.


## Conclusions
Three models have been created as part of the project and below conclusions can be derived out of those:
- Model 1: When default dataset is used then it leads to an over-fitted model.
- Model 2: Data-augmentation is used which removes over-fitting but the train/validation accuracy numbers are still low. Analysis shows that 
           there is data imbalance which causes this issue.
- Model 3: Data rebalancing is done on the dataset which helps to solve both the above issues (overfitting & accuracy)


## Technologies Used
- Tensorflow framework is used to build the CNN model
