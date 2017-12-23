# Face Detection
- 
- please check out the .mp4 video!
## Introduction:
**Background:** 
In recent years, face detection problem has been more and more popular and attractive to almost every single person in modern society. Face detection system is a computer application capable of identifying or verifying a person from a digital image or a video frame from a video source. One of the ways to do this is by comparing selected facial features from the image and a face database. Since I really interested in face detection field, I would like to begin this project to do facial detection by building model myself.

**Object of this project:** 
Accomplish facial detection implementation by using machine learning knowledges, especially convolutional neural network.

**My idea:** 
At first, I would like to create a fully connected CNN (no FC layer at all), and then train this neural network on small images and set up CNN to output a 1x1x1 output. Then run the CNN on larger image, it will output the score for each box in the input image. While I would like to start my project with a more basic model, I append FC layers after CNN layers in my model. I build this model with the following steps:

- step1: Transfer learning from well-known model (VGG-16), this could save our time to train model from scrach.
- step2: Add our own layers (FC layers) to VGG-16 and obtain our model.
- step3: Download human pictures and generate face images as part of training samples.
- step4: Training model

After model being built, I try to:
- step1: Single face detection
- step2: Multi face detection
