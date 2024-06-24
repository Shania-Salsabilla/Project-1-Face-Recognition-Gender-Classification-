# Project-1-Face-Recognition-Gender-Classification-
This project focuses on gender classification using face recognition techniques, leveraging the CelebA dataset. It involves experimenting with three popular deep learning algorithms: VGG, GoogLeNet, and ResNet, to determine the best model for gender classification.

## Overview:
In this digital era, face recognition technology is growing rapidly and is being applied in various fields. One of its applications is gender classification, which is identifying the gender of a person from an image or video. This technology has great potential to improve security and efficiency in various applications, such as attendance systems, access control, demographic analysis, and others.

## Features:
- `Dataset`: Utilizes the CelebA dataset which contains images of 5,017 celebrities with various attributes.
- `Deep Learning Model`: Implements VGG (VGG-11, VGG-13, VGG-16, VGG-19), GoogLeNet (Inception V1, Inception V3), and ResNet (ResNet-18, ResNet-34, ResNet-50, ResNet-101).
- `Preprocessing`: The CelebA dataset will be preprocessed with steps such as resizing, imbalancing, and data augmentation.
- `Model Training`: Each deep learning algorithm will be trained with the preprocessed CelebA dataset with three different treatments:   
   1. Pretrained model with BCEWithLogitsLoss criterion.   
   2. Non-pretrained model with BCEWithLogitsLoss criterion.   
   3. Non-pretrained model with CrossEntropyLoss criterion.
- `Model Evaluation`: The performance of each model will be evaluated with accuracy, precision, recall, and F1-score metrics.
- `Conclusions`: The best algorithm and treatment will be selected based on the highest evaluation performance.
