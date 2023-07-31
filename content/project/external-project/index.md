---
title: Pneumonia Detection using Deep Learning
summary: Detecting Pneumonia in X-ray images of lungs using deep learning architectures likes ResNet, DenseNet and SqueezeNet.
tags:
  - Computer Vision, CNNs
date: "2020-12-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption:
  focal_point: Smart

links:
  - icon: Github
    icon_pack: fab
    name: Link
    url: 'https://www.ingentaconnect.com/contentone/asp/jctn/2020/00000017/00000012/art00043'
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

---
This paper presents an in-depth study of Pneumonia detection using Chest X-rays and machine learning algorithms, including SqueezeNet, DenseNet, and Resnet34. The study's aim was to automate the process of pneumonia diagnosis using a convolutional neural network (CNN). This is accomplished by image processing methods such as pre-processing, edge detection, morphological processing, and feature extraction, followed by the use of CNN models for classification.

The study utilized the Kaggle chest X-ray pneumonia database, containing 5,863 chest X-ray images categorized as Pneumonia and Normal. Various image processing techniques were employed, including image acquisition, enhancement, restoration, and color image processing. Additionally, methods such as Gaussian blur, bilateral filtering, and Canny edge detection were used for image augmentation and improvement.

The paper also elaborates on the CNN architecture, detailing the roles of convolutional layers, pooling layers, and fully connected layers. Moreover, an explanation of the functionality and benefits of different models (ResNet34, SqueezeNet, and DenseNet) is provided.

The results of the experiment indicated that DenseNet had the highest testing accuracy of approximately 97.44%, making it the most efficient model for this application. While the training time for DenseNet was longer than SqueezeNet, its superior accuracy made it a better choice for pneumonia detection in Chest X-rays.