
# Tennis Analysis

## Introduction
This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints. This hands on project is perfect for polishing your machine learning, and computer vision skills. 

## Output 
screenshot.jpeg




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



![image](https://github.com/saiabhinay77/Tennis-Player-Analysis-with-YOLOv8/assets/85699213/a4f3282a-8547-4a97-804c-31bf6e165717)

![clay462_jpg rf 0c0a6b1d8b36d949064c78416a919941](https://github.com/saiabhinay77/Tennis-Player-Analysis-with-YOLOv8/assets/85699213/2ddbe16b-330b-4e46-a4d6-e3c00db4702d)

## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
