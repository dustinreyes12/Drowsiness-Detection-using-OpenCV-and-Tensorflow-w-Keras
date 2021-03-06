# Drowsiness Detection using OpenCV and Tensorflow w/ Keras

The project is divided into two main parts: Training a convolutional neural network model that can correctly classify whether the eyes of a person are open or closed and using the trained model to provide real-time video classification about the user's state on whether he/she is drowsy.

A threshold score is implemented which identifies that the user is drowsy with the score incrementing one step at a time as long as the eyes are closed and with the score decrementing if the eyes are then opened. 

An alarm system was also created to alert the user that he/she is already drowsy and is in danger of falling asleep. The model used for eye state classification achieved an average of 95% test accuracy. 

The goal of the project is to detect drowsiness which will serve to reduce drowsy driving and unproductivity due to drowsiness at the workplace. By preventing the occurrence of these scenarios, the project will surely help in the reduction of events related to drowsiness
