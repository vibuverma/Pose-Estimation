# Pose-Estimation

Pose Estimation <br>
Pose estimation is the task of using an ML model to estimate the pose of a person from an image or a video by estimating the spatial locations of key body joints (keypoints).
<br>

libraries:</br>
-->  opencv-python</br>
-->  mediapipe</br>

Mediapipe:</br>
The solution utilizes a two-step detector-tracker ML pipeline,using a detector, the pipeline first locates the person/pose region-of-interest (ROI) within the frame. The tracker subsequently predicts the pose landmarks within the ROI using the ROI-cropped frame as input.
