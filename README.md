# Project-1-Face-Recognition-Gender-Classification-
![Face Recognition](https://github.com/user-attachments/assets/7c036fa2-795e-4618-9681-7b06856990e6)

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

## Folder Structure:
- `Images`: A folder containing images of 5017 celebrities with some duplicates.
- `class_identity.txt`: A text file containing class identity information for each image.
- `gender_classification.csv`: A CSV file containing gender classification information for each image.
- `gender_classification.xlsx`: An Excel file containing the gender classification information for each image.
- `list_attribute_original`: A text file containing most of the facial attribute data from the image.
- `list_attribute_edit`: An edited text file of the original list_attribute_ with the file_name added and the `Male` column changed from -1 to 0.
- `NoPretrain BCE Models`: Folder containing models trained without pretrain with BCEWithLogitsLoss criterion.
- `Models Pretrain BCE`: Folder containing models trained with pretrain models with BCEWithLogitsLoss criterion.
- `Models NoPretrain CE`: Folder containing models trained without pretrain with CrossEntropyLoss criterion.
- `validation_images`: Folder containing validation images.
- `Pretrain Model Validation Data`: A folder containing validation data for models trained with model pretrain.
- `PPT CelebA After Revision.pptx`: Powerpoint of the presentation that has been done.
- `Project 1_ Face Recognition Timeline & Results`: Excel file of the project timeline and results of the comparison of the models.

## Expected Results:
- An accurate and efficient gender classification model with more than 90% accuracy.
- Performance comparison of three popular deep learning algorithms: VGG, GoogLeNet, and ResNet.
- Comparison of model training performance with pretrain, without pretrain with BCEWithLogitsLoss, and without pretrain with CrossEntropyLoss.
- Conclusions on the best algorithms and treatments for the gender classification task on the CelebA dataset.
