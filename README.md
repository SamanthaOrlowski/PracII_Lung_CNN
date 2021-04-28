# PracII_Lung_CNN
Lung PET Scans CNN Model

<br>Image classification is the act of classifying an image based on a class that has been identified. In the medical world, image classification takes a step further to make diagnosis for patients with potential life threatening conditions. </br>

Image registration is aligning, matching or fusing two images together and finding the best end image that aligns the two initial images. In the past, image registration has been done by hand. However, the recent machine learning/deep learning boom has created new methods to complete image registration by using a model. 

<img width="807" alt="Readme screenshot" src="https://user-images.githubusercontent.com/60263324/116445682-61960a00-a813-11eb-9a01-dc4b531b9f7f.png">
Image courtesy of Deep Learning in Medical Image Registration: A Survey. Recent increase in deep learning in the medical field.


<br>Deep learning is primarily used in the medical field in order to have multiple neural network layers that can learn representations of data. There are multiple kinds of deep learning methods that can be used: deep iterative registration, supervised transformation estimation, and unsupervised transformation estimation.</br>

The dataset involved in this model contains CT and PET scans of Lungs that contain masses. Based on this dataset a Fully Convolutional Network (FCN) supervised transformation estimation model should be used. However, a FCN model is primarily used for CT scans and not PET scans. Therefore, a CNN supervised model will be used instead.

## Layout of this Github

### Development:

LungCNN.ipynb - Contains the current CNN model for the Lung Cancer diagnosis. 

DeprecatedMaskRCNN.ipynb - contains the deprecated MaskRCNN model that ended up not being used. 
Lots of the LungCNN model preprocessing was used from this deprecated model.

#### Dicom files and annotations for this repo can be retrived from here:
 https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70224216
