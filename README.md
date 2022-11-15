# Project Name
> Melanoma Detection Assignment
Use Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The current analysis is based on the "Skin cancer ISIC The International Skin Imaging Collaboration" dataset. It consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.

## Technologies Used
- Keras
- TensorFlow
- Python 3
- Pandas, Numpy, Matplotlib,
- Augmentor

## Conclusions
We managed to eliminate overfitting and managed to reach a decent accuracy by using:
- Data augmentation
- Managing Class imbalance
- Using Dropout Layers
- Using Batch Normalization

## References
- https://keras.io/guides/
- https://www.tensorflow.org/tutorials/images/data_augmentation
- https://augmentor.readthedocs.io/en/stable/

## Contact
Created by [@sivaprasadt246] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
