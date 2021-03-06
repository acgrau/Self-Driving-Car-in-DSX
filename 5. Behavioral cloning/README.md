# Use Deep Learning to Clone Driving Behavior

Overview
---
In this project we Train, validate and test a model using Keras to clone driving behavior. The model will output a steering angle to an autonomous vehicle.
Data will be collected by running a car manually in Udacity's Self-Driving Car simulator. The model performance will be tested by running the car in the simulator in autonomous mode.

#### The goals / steps of this project are the following:

* Use the simulator to collect data of good driving behavior
* Build, a convolution neural network in Keras that predicts steering angles from images
* Train and validate the model with a training and validation set
* Test that the model successfully drives around track one without leaving the road
* Summarize the results with a written report

Project Deliverables
---
* `model.py` contains the code for building the keras model based on the [Nvidia architecture](https://devblogs.nvidia.com/parallelforall/deep-learning-self-driving-cars/). 
* `model.h5` is the trained keras model needed to run the vehicle autonomously.
* `drive.py` is used to drive the vehicle autonomously in the simulator. It accepts an h5 file as a parameter.
* `video.mp4` is the video produced from the vehicle's camera view during the autonomous run.
* `video_rear.mp4` is the video of the same run looking at the vehicle from behind.

Model Architecture
---
I based my model on the [Nvidia architecture](https://devblogs.nvidia.com/parallelforall/deep-learning-self-driving-cars/). It includes a normalization layer, 5 convolutional layers,1 dropout layer, and finally 3 fully connected layers. 
Through this model, the vehicle was able to drive autonomously around the track without leaving the road or diving into water and making smooth turns around corners.

Results
---
View the **[video](https://www.youtube.com/watch?v=MB-ii0qzUmQ)** on Youtube

