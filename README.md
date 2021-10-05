# Pose-Estimation


Pose Estimation <br>
Pose estimation is the task of using an ML model to estimate the pose of a person from an image or a video by estimating the spatial locations of key body joints (keypoints).
<br>

libraries:</br>
-->  opencv-python</br>
-->  mediapipe</br>

Mediapipe:</br>
The solution utilizes a two-step detector-tracker ML pipeline,using a detector, the pipeline first locates the person/pose region-of-interest (ROI) within the frame. The tracker subsequently predicts the pose landmarks within the ROI using the ROI-cropped frame as input.
### Steps:
Fork the project into your own Repository and using Github Desktop Clone this project wherever you like.
<img src="https://www.slashgear.com/wp-content/uploads/2019/08/google-mediapipe-1280x720.jpg" width="1000" height="600">






# Installation
- Firstly create a new python 3.6 Environment by using the command ```conda create -n myenv python=3.6```
- Secondly Activate the environment by using command ```conda activate myenv```
- Thirdly run command to install mediapipe ```pip install mediapipe```
- Fourthly Activate python runtime by using ```python```.
- Then run a requirements.txt file by using command
```pip install -r requirements.txt```
- Afterwards run the App.py file using command ```Pose_Estimation.py```.
# Web Deployment
- Log into your Heroku Account.
- Click on ```create New App```
- Choose ```Location``` and finally click on ```create app```
- Choose Deployment method as Github and login into your github account and fork the desired repository to prepare the pipeline.
- Result can be viewed by clicking on the App link which was generated.
