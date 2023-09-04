
# YOLOv8DeepSort-Basketball-Training

Object detection and tracking using neural networks
for individual basketball training

In this repo we use two diferents repos:

+ [YOLOv8](https://github.com/ultralytics/ultralytics)
+ [YOLOv8-DeepSORT-Object-Tracking](https://github.com/MuhammadMoinFaisal/YOLOv8-DeepSORT-Object-Tracking)

From this I've created a python script that can detect a person and ball from a video and give a feedback.
## Installation

+ First of all clone this repo
```
git clone https://github.com/Mario31y/YOLOv8DeepSort-Basketball-Training
```
+ Second install all the dependencies
```
pip install -r requirements.txt
pip install ultralytics
```
    
## Run

To test this project follow the next steps:

- Setting the Directory.
```
cd yolo/v8/detect
```

- Do Tracking with mentioned command below

You can use any YOLO-v8 model or train001.pt and train001l.pt two models that work well with the test videos. There are 3 excercise types.
```
python tracking_ball_person_counting.py model=yolov8l.pt source="videos/test.mp4" show=True
```
```
python tracking_ball_person_counting1.py model=yolov8l.pt source="videos/test.mp4" show=True
```
```
python tracking_ball_person_counting2.py model=yolov8l.pt source="videos/test.mp4" show=True
```

