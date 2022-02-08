# Computer-Vision-Rock-Paper-Scissors

## Overview
This in an interactable Rock-Paper-Scissors game written in python, in which the user can play with the computer using the camera. The game logic is simple, hold your option (Rock, paper or scissor) until the program recognizes your choice and the result will immediately come out. Repeat it until you or computer wins 3 times. You may always press 'q' to quit the game. 

Please follow the instruction on the jupyter notebook to setup the environment and how to start the game. 

## Model
The machine learning model I am using is provided by Teachable machine (https://teachablemachine.withgoogle.com/train) and trained by myself. Since deep learning requires a huge amount of data to improve the performance, the recognization may not work for you as I trained the model with only my web cam captures. To improve the performance, you can train the model on Teachable machine with 4 classes (Rock, Paper, Scissors and None) with your webcam captures, download Tensorflow Keras model and replace the model folder. You may upload project.tm into Teachable machine to see how the training data looks like and train your model for better performance. 

## Libraries
We use the following libraries () is the version of my testing environment:
- Python 3 (3.9.10)
- OpenCV (4.5.3)
- Tensorflow (2.6.0)
- Numpy (1.19.5)
- cvzone (1.5.5)
- mediapipe (0.8.9.1)

Since mediapipe doesn't support Mac M1, the hand tracking module will only work on Mac Intel, Windows and Linux (I only tested it on Mac Intel). The environment setup will be failed but the code will still work without hand tracking module. 

We suggest to create a conda environment but you still setup with the libraries listed above in your envrionment as you like.  
