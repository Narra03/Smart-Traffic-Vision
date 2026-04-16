# Smart-Traffic-Vision

Computer vision-based traffic analysis system using YOLOv8 for vehicle detection, video inference, and class-wise traffic analytics.

## Overview

This project implements an end-to-end computer vision pipeline for analyzing traffic using video data. A YOLOv8-based object detection model is trained and applied to traffic videos to detect vehicles and generate class-wise traffic insights.

## Objectives

- Detect vehicles such as cars, trucks, buses, motorcycles, and ambulances from video streams
- Perform class-wise traffic analysis
- Convert unstructured video data into structured outputs
- Visualize traffic patterns

## Features

- Custom-trained YOLOv8 model
- Video-based object detection
- Class-wise vehicle counting (frame-wise)
- CSV-based structured data generation
- Traffic pattern visualization

## Tech Stack

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Pandas
- Matplotlib

## Results Achieved

- Achieved approximately 0.58 mAP in the initial training run
- Generated class-wise traffic insights from video
- Successfully processed real-world traffic footage

## Project Structure

```text
smart-traffic-vision/
├── models/
│   └── best.pt
├── videos/
│   └── traffic_output.mp4
├── outputs/
│   └── traffic_class_analysis.csv
├── notebooks/
│   └── train_yolo.ipynb
├── requirements.txt
└── README.md
