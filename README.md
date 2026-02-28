# Traffic Object Detection using YOLOv26 (NMS-Free)

## Overview
This project implements the YOLOv26 object detection architecture using a custom traffic-related dataset annotated and preprocessed via Roboflow. The model is trained and evaluated in Google Colab using the Ultralytics framework with a focus on performance diagnostics and real-world readiness.

## Dataset
- Annotation Tool: Roboflow
- Format: YOLOv26
- Classes: Traffic-related objects
- Dataset split: Train / Validation / Test
- Dataset access: Provided via cloud link: https://drive.google.com/drive/folders/18aOJ6r0tLHJRqyTNxdDuNjyFKjUC19u0?usp=sharing 

## Methodology
- Model: YOLOv26 (NMS-Free Detection)
- Image size: 640 × 640
- Epochs tested: 25, 30, 40
- Optimizers: AdamW, SGD, Auto
- Learning rates: 0.01, 0.001, 0.0001
- Batch sizes: 4, 20, Auto

## Evaluation Metrics
- mAP@50
- Precision
- Recall
- F1 Score
- Confusion Matrix Analysis

## Repository Structure
traffic-yolov26-detection/
├── dataset/
├── notebooks/
├── reports/
└── README.md


## Results
Performance results, confusion matrices, and comparative model discussions are documented in the `reports/` directory.

## Tools & Libraries
- Python
- Google Colab
- Ultralytics YOLO
- Roboflow
- Pandas, Matplotlib

## Author
Course Project – Object Detection using YOLOv26
