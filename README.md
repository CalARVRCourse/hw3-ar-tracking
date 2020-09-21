# HW3: AR Tracking and 3D Reconstruction with OpenCV

For this homework you will be implementing pose estimation of a known image using OpenCV. You will then adapt this pose estimation algorithm to compute a sparse point cloud representation of a scene. This homework is intended to give you a basic introduction to computer vision as it relates to augmented reality. This includes concepts such as camera calibration, feature matching, perspective projection, and 3d point cloud estimation. 

In this homework you will be guided through most of the steps to implement AR pose estimation of a known image, but you will be asked to implement one basic function based on the concepts we introduced in class. You will then use what you have learned to develop a system for sparse point cloud reconstruction of a scene using your mobile device. These steps represent a simplified set of functions that form the basis of modern AR tracking. 

Note: This document was written using OpenCV 3.4.7. Some changes may be required for alternate versions of OpenCV.
 

## Logistics

After you have accepted the assignment, a seperate repo "hw3-ar-tracking-YourGitID" should have been created. You will push your assignment code to this, and this will be used for grading.

### Deadline

HW2 is due Friday 10/02/2020, 11:59PM. Both your code and video need to be turned in for your submission to be complete; HWs which are turned in after 11:59pm will use one of your slip days -- there are no slip minutes or slip hours.

### Academic honesty
Please do not post code to a public GitHub repository, even after the class is finished, since these HWs will be reused both  in the future.

This HW is to be completed individually. You are welcome to discuss the various parts of the HWs with your classmates, but you must implement the HWs yourself -- you should never look at anyone else's code.

## Deliverables:

### 1. Video
You will make a 2 minute video showing off the features of your game. The video must include a verbal description of your project and it’s features. You must also include captions corresponding to the audio. This will be an important component of all your homework assignments and your final project so it is best you get this set up early. 

We recommend using a screen recorder to record video of your game in action. 
For iOS you can use the built in screen recorder: https://support.apple.com/en-us/HT207935 
For Android devices you will likely want to install a 3rd party screen recorder. AZ Screen Recorder works well and is easy to use: https://play.google.com/store/apps/details?id=com.hecorat.screenrecorder.free&hl=en_US 

### 2. Code
You will also need to push your project folder to your Github Classroom assignment's repo.


## Before You Start:


For this homework you will need Python and OpenCV. After installing Python, to install OpenCV: 
In command prompt/ terminal run:

```python
pip install opencv-contrib-python
```

(you may need to add sudo for unix systems). 

## Instructions

Instructions for setting up the starter code are availoable at the google docs file at https://docs.google.com/document/d/1dNhCcNOpxptHb9oq8h5POKWJUk09LzXlRDgXhROqwts



