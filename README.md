#Behavioral Cloning Project
The goals / steps of this project are the following: -
	_Use the simulator to collect data of good driving behavior
	_Build, a convolution neural network in Kera’s that predicts steering angles from images
	_Train and validate the model with a training and validation set
	_Test that the model successfully drives around track one without leaving the road
	_Summarize the results with a written report


Except for resizing of images for ease of training, no other preprocessing is done on the images. No image augmentation techniques like flipping etc was also not undertaken. As no heavy preprocessing and augmentation of images is undertaken, generators are not used in the code. (As I generated lot of data using different techniques, I felt there is no need for augmentation)

My project includes the following files: -
	_model.py containing the script to create and train the model
	_drive.py for driving the car in autonomous mode
	_model.h5 containing a trained convolution neural network 
	_writeup_report.pdf summarizing the results
