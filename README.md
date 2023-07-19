# Melanoma Detection
>  Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- . Skin cancer is a type of cancer that grows in the skin tissue, which can cause damage
to the surrounding tissue, disability, and even death. In Indonesia, skin cancer is the third
leading for most cancer cases after cervical and breast cancer. The accuracy of diagnosis and the
early proper treatment can minimize and control the harmful effects of skin cancer. Due to the
similar shape of the lesion between skin cancer and benign tumor lesions, physicians consuming
muchmore time in diagnosing these lesions. The systemwas developed in thisstudy could identify
skin cancer and benign tumor lesions automatically using the Convolutional Neural Network
(CNN).

- . The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Conclusions
- Data Augmentation, Handling imbalance in the data using augmentor and Batch Normalization techniques helped in improving model performance


## Technologies Used
- tensorflow - version 2.13.0
- keras - version 2.13.1


