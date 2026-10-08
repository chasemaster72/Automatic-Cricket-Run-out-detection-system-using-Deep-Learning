# Cricket-Run-out-detection-system
## 📖 Overview
The system analyzes cricket frames to determine whether the batsman is **OUT or NOT OUT** based on the position of the batsman and crease.

## 🚀 Features
- Detects batsman, stumps, and relevant objects using YOLO
- The detected object positions are then used to analyze the **batsman’s position relative to the crease and stumps** for run-out decision making.
- Classifies frames as OUT / NOT OUT using MobileNetV2
- Supports image based analysis
- Uses transfer learning for efficient classification

## 🛠️ Technologies Used

- Python
- YOLO
- MobileNetV2
- OpenCV
