# Melanoma Detection

To build a Convolutional Neural Network (CNN) which can accurately detect Melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [Dataset Info](#dataset-information)
* [Libraries Used](#libraries-used)
* [Hardware Accelerator Used](#hardware-accelerator-used)
* [Acknowledgements](#acknowledgements)
* [Project Collaborators](#project-collaborators)

## Dataset Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the *International Skin Imaging Collaboration (ISIC)*. All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The dataset contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Libraries Used
- tensorflow 2.11.0
- numpy 1.22.4
- pandas 1.3.5
- Matplotlib 3.5.3
- seaborn 0.11.2

## Hardware Accelerator Used
Nvidia A100 Tensor Core GPU
- CUDA Version: 12.0
- Driver: NVIDIA-SMI 525.85.12

## Acknowledgements
We would like to express our deepest appreciation to Karen Simonyan & Andrew Zisserman for their research paper: [Very Deep Convolutional Networks for Large-scale Image Recognition](https://arxiv.org/pdf/1409.1556.pdf).


## Project Collaborators
- Sachin Shekhar
- Srija Palakurthi
- Pritesh Kudalkar
