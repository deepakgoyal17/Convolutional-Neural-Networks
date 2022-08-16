**Problem statement**: 

To build a CNN based model which can accurately detect melanoma. 
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


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

**Conclusions:**

Model we have created is able to provide an accuracy of 88% on train and 79 % on validation data. Though we could increase the accuracy by adding more layers and neurons, doing dropouts and batch normilizations etc.

Model was created using some of the agumentation techniques to increase the accuracy and avoid overfitting.

