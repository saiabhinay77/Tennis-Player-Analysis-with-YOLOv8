
# Tennis Analysis

## Introduction
This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints. This hands on project is perfect for polishing your machine learning, and computer vision skills. 

## Input 


![image](https://github.com/saiabhinay77/Tennis-Player-Analysis-with-YOLOv8/assets/85699213/204a4647-3a9a-425c-b15e-ff67d738baf8)


## Output 

![screenshot](https://github.com/saiabhinay77/Tennis-Player-Analysis-with-YOLOv8/assets/85699213/36948c8b-d59b-468f-bd02-075275048e1b)








## Models Used
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

* Trained YOLOV5 model: https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing
* Trained tennis court key point model: https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing

## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb
![image](https://github.com/saiabhinay77/Tennis-Player-Analysis-with-YOLOv8/assets/85699213/0fd887fc-af28-47eb-aa98-b8c270b73d77)

Pose Analysis and Performance Insights:

With the keypoints identified, you can now analyze the player's pose in detail. By connecting these keypoints, you can visualize the player's posture and track their movements throughout the video.
This data can be used to gain insights into various aspects of a tennis player's performance:

Swing mechanics: Analyze the angles of the arm and body during a forehand or backhand swing to identify potential improvements.
Body positioning: Track the player's movement during footwork drills or rallies to assess balance and efficiency.


![image](https://github.com/saiabhinay77/Tennis-Player-Analysis-with-YOLOv8/assets/85699213/a4f3282a-8547-4a97-804c-31bf6e165717)

Real-Time Processing:
Immediate Feedback: Tennis coaches rely on providing immediate feedback to players to correct technique issues. Real-time analysis allows coaches to point out errors in swings as they happen, leading to faster improvement.

Action Recognition:
Object Detection vs. Action Recognition: While YOLOv8 excels at object detection (identifying objects in an image/video), it can also be adapted for action recognition.
Training the Model: An action recognition model for tennis swings would be trained on a large dataset of labeled videos. Each video would be segmented and labeled with the specific swing type (forehand, backhand, serve, etc.).
Model Predictions: During analysis, YOLOv8 would process each video frame and predict the most likely action (swing type) happening based on the pose and movement of the player.

Automated Swing Classification: The model can automatically categorize different swing types, reducing the need for manual analysis by coaches. This saves time and allows for more focus on detailed technique evaluation.
Data Collection and Performance Tracking: Action recognition enables automatic data collection on swing types performed during practice sessions. This data can be used to track a player's progress, identify swing tendencies, and measure the effectiveness of training programs.
Highlighting Specific Actions: The model can be used to filter and highlight specific swing types (e.g., only focus on backhand swings) for targeted analysis. This allows coaches to delve deeper into a particular swing and identify areas for improvement.


## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
