# Vehicle Detection and Tracking
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

### The goals / steps of this project are the following:
* Read the data set containing vehicles and non-vehicles images.
* Extract histogram of gradient (HOG) features using a proper color channel.
* Spatial distribution of colors (binned color features) and histogram of colors may also be applied.
* Use a LinearSVC or a SVC(kernel='rbf') to classsify vehicles and non vehicles objects and evaluate accuracy score.
* Use a sliding window search technique to a region of interest frame by frame to detect vehicles.
* Use heatmap and thresolding to remove outliers and false positives.
* Predict the co-ordinates and draw a bounding box to each vehicles.
* Now apply the above steps to a video file and draw bounding boxes to each file.

**Environment specification :**

* OS used : Ubuntu Linux 16.04 LTS
* This project is done in python version 3.6.2 .
* Don't use python version < 3.6 . The f-string function will not work properly.
* Scikit learn version used => 0.19.0

### Discussions
**Reading the datasets and Explore data**:
                 
     1. Read the whole dataset using read_vnv_data() function for training.
     2. 
 ![Image 1](./re
