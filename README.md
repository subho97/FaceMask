# FaceMask Detection
Amidst the ongoing crisis, it's very important for each one of us to maintain safety protocols because at the end, if we stay safe others stay safe. Wearing a Face Mask is one such protocol we all must follow. This repository contains the files and documents that are required to fine-tune a MobileNetV2 CNN architecture to recognise faces and determine whether the person is wearing a mask or not. It works on still images as well as on live webcam stream in real-time.

I will be breaking down the entire project into three simple and intersting steps.

#Step 1: Loading our dataset- We will be loading in our train, validation and test sets into the Convolutional Neural Network to help it to learn how a face with and without a mask looks like. The validation set will help us to fine tune our results and get the best possible accuracy. The test set will be the final test for the model.

#Step 2: Loading the MobileNetV2 architecture - MobileNetV2 architecture is optimised for mobile devices. The architecture delivers high accuracy results while keeping the parameters and mathematical operations as low as possible to bring deep neural networks to mobile devices. It is a very effective feature extractor for object detection and segmentation. In short, it's a light weight, high accuracy model for Image Classification which is exactly why we are going to use it in this project.

#Stage 3: Apply the fine-tuned CNN on new images/live video stream - Once the CNN Model is ready, fresh and new images can be passed through it to classify them between people wearing a mask and people not wearing a mask. The project also includes the code to capture the live video stream from the local webcam and apply the model on the on each Image frame of the video to get a real-time classification.
  
Happy Coding !
