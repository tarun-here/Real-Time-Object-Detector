# Real-Time-Object-Detector
**Demo**



*This video demonstrates the real-time object detection capabilities of  model.*

**Description**

This project showcases a real-time object detection system built using YOLOv5s. While I was going to use YOLOv10 but with limited dataset, I used YOLOv5. I got a good overall validation result as mentioned below.

**Results**

| Class      | Images | Instances | P      | R       | mAP50  | mAP50-95 |
| ----------- | -------- | ----------- | -------- | -------- | -------- | ---------- |
| all        | 29      | 52        | 0.892  | 0.933   | 0.932  | 0.837     |
| Phone      | 29      | 7         | 0.803  | 0.857   | 0.859  | 0.725     |
| Speaker    | 29      | 17        | 0.909  | 0.941   | 0.944  | 0.919     |
| Tarun      | 29      | 28        | 0.963  | 1       | 0.993  | 0.868     |

**Dataset**

  I made my own custom dataset which I annotated using Roboflow. I had 100 clicked images and 2 videos which, I augmentated and got total of 431 images. I used extra objects in training and validation images
  
**Acknowledgment**

 The YOLOv5 project ([https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5))
