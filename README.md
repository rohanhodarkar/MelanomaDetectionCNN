# Project Name
> Building a CNN based model which can accurately detect melanoma. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
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

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The dataset is highly impalance with "seborrheic keratosis" having least number of samples i.e. 77  whereas "pigmented benign keratosis" with 462 and "melanoma" with 438 dominate the entire dataset
- An augmentor to synthetically increase the class count helps in building an efficient model.
- A CNN model with appropriate filters, hidden layers and droptout helped overcome overfitting problem with this solution.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow - version 2.12.0
- Keras - version 2.12.0
- Augmentor - version 0.2.12
- Matplotlib - version 3.7.1
- Seaborn - version 0.12.2
- PIL - version 3.7.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@rohanhodarkar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->