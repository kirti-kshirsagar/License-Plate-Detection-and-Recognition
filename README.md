# Vehicle License Plate Detection and Recognition System

## Project Overview
This project involves the development of a vehicle license plate detection and recognition system using advanced machine learning techniques. The system uses YOLOv8 for object detection and EasyOCR for optical character recognition.

## Key Features
- **Object Detection**: The system is trained on a dataset of **395 vehicle images from ultralytics, roboflow in YOLOv8 format**, to accurately detect license plates in various sizes, orientations, and lighting conditions.
- **Optical Character Recognition**: The system implements **EasyOCR** to convert images of license plates into machine-readable text, enabling the extraction of alphanumeric characters with high accuracy.
- **Performance Analysis**: The system's performance is analyzed through various metrics such as **precision, recall, and Mean Average Precision (mAP)**, ensuring the model's reliability and stability over time.

## Results
- The model achieved **high precision and recall rates**, indicating its good performance in identifying relevant instances and the proportion of actual positives identified correctly.
- The model attained **high mAP at IoU threshold 0.50 (mAP50) and across IoU thresholds from 0.50 to 0.95 (mAP50-95)**, suggesting that the model is consistent in detecting objects accurately across different intersections over union (IoU) thresholds.
- The system demonstrated its **effectiveness on videos**, processing individual frames to detect and identify objects, crucial for real-time or near-real-time detection.
