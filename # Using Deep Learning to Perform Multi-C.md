# Using Deep Learning to Perform Multi-Class Classification on the Covid19 Chest X-ray Dataset

## Context
Machine and Deep Learning can be used to assist in diagnosing specific lung infections. In this project, we were provided with a baseline Convolutional Neural Network (CNN) model, and our task was to improve this baseline model's ability to accurately predict lung infections. Various approaches like data augmentation techniques, early stopping, dropout, class weights, and regularization techniques were tested. Additionally, through transfer learning, the feature learning layers of an extensively trained CNN on a different dataset were "transferred" to this project.

### Dataset
The dataset contains 6500 images of AP/PA chest x-rays with pixel-level polygonal lung segmentations. There are 4 different classes in the dataset (Bacterial Pneumonia, Viral Pneumonia, No Pneumonia (healthy), Covid-19).
Image resolutions, sources, and orientations vary across the dataset, with the largest image being 5600 × 4700 and smallest being 156 × 156. For the purpose of this project, all images were resized to 156 x 156.