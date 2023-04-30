# Multiple Object Tracking using Machine Learning (MOT)

  In this project we are going to tracking multiple abnormal objects. Footage or data that we are using will be of stationary camera mounted at pedestrian walkways.The crowd density in the walkways was variable, ranging from sparse to very crowded. Abnormal crowd event can be classified into two groups on the basis of a scale of interest: global anomalous event and local anomalous event.

## Dataset
We have used UCSD Anomaly Detection Dataset in this project. It consists of dataset which was split into 2 subsets, each corresponding to a different scene. The video footage recorded from each scene was split into various clips of around 200 frames.

Peds1: clips of groups of people walking towards and away from the camera, and some amount of perspective distortion. Contains 34 training video samples and 36 testing video samples.

Peds2: scenes with pedestrian movement parallel to the camera plane. Contains 16 training video samples and 12 testing video samples.

## Dependancies
        python3.6
        cv2
        scikit-learn
        pandas
        numpy
        
## Execution
 
        python3 video_classifier.py
        
## Result
![result](https://user-images.githubusercontent.com/112248684/235342904-a2a9fcb6-6ca4-487c-9179-7523e43f2c5e.gif)
