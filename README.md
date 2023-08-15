# Keystroke-Analysis-for-Password-Authentication
With the incessant rise in cybercrimes, protecting our online data has become increasingly difficult.

Currently, to login to your account we have to enter a password. Some cautius uses have a 2-factor authentication system wherein you get an OTP on your phone. It was very easy for a hacker with the right tools to gain access to your account within minutes.

To tackle this problem, I have implemented a new method of authentication.

In this project, I am using the inherent typing rhythm of a person to authenticate her.

The hypothesis is that each person has a very specific rhythm (similar to having unique handwriting). I am analyzing the patterns in keystrokes to identify the user.

# Features
The typing features that I have utilized for analysis are as follows:

Key UP- Key UP, Key UP- Key DOWN, Hold, Enter

# Models Implemented
I have implemented 3 models - SVM, Neural network, Manhattan Detector

Support Vector Machine

Neural Network

Manhattan Detector

It calculates loss as the Manhattan distance between the test mean vector and train mean vector divided by the mean absolute deviation

# Model Evaluation:

Then I evaluated the model using several metrics - all three gave good accuracy

SVM                  91%                  0.09

Manhattan        89%                 0.102

Neural               83.9%               0.161

So out of these three SVM gave the highest accuracy.

So we managed to correctly authenticate the users based on their typing rhythm by 91%
