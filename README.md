# Deepfake_Image-Detection

Deepfake Image Detection using CNN
This project focuses on detecting deepfake images using Convolutional Neural Networks (CNN). With the increasing threat of manipulated media, especially in the form of deepfakes, this project aims to build a robust image classification model that can accurately distinguish between real and fake images.


Dataset:

Train: Contains images used to train the CNN model.

Real: Images that are genuine (non-deepfake).
Fake: Images that are manipulated or synthetic (deepfakes).

Validation: Used to tune the model during training and monitor for overfitting.

Real: Genuine images for validation.
Fake: Fake images for validation.

Test: Used to evaluate the model after training is complete.

Real: Genuine test images.
Fake: Fake test images.


Model Architecture:

Input Layer (Image: 128x128 or resized as per code)
Multiple Conv2D + MaxPooling2D layers
Dense layers with ReLU activation
Output layer with sigmoid (binary classification)


Dataset link:
https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images

