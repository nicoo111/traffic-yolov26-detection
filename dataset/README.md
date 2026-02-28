# Traffic Object Detection Dataset

## Dataset Overview
This dataset is designed for traffic-related object detection using the YOLOv26 architecture. Images were collected from publicly available traffic scenes and annotated using Roboflow.

## Classes
- SUV
- Car
- Human
- Motorcycle
- Bicycle

## Annotation Process
- Tool: Roboflow
- Annotation type: Bounding boxes
- Format: YOLO (v26-compatible)
- Quality checks performed to ensure accurate bounding boxes and correct class labels

## Dataset Structure
dataset/
├── train/
├── valid/
├── test/
└── data.yaml

## Preprocessing
- Image resizing to 640×640
- Normalization handled by YOLO pipeline
- Data augmentation applied via Roboflow (flip, scale, brightness adjustments)
- Noise reduction applied implicitly through preprocessing

## Class Balancing
Initial analysis showed class imbalance across traffic object categories. Dataset balancing was addressed using:
- Augmentation for underrepresented classes
- Controlled sampling during dataset export

## Access
Due to size constraints, the full dataset is hosted externally:
- Roboflow project link: (insert link)
- Google Drive link: (insert link)

## Notes
Only the configuration file (`data.yaml`) and documentation are included in this repository.
