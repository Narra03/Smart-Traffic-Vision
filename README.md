# Smart-Traffic-Vision
Computer vision-based traffic analysis system using YOLOv8 for vehicle detection, video inference, and class-wise traffic analytics.
Smart Traffic Analysis using Computer Vision (YOLOv8)
📌 Overview

This project implements an end-to-end computer vision pipeline for analyzing traffic using video data. A YOLOv8-based object detection model is trained and applied to traffic videos to detect vehicles and generate class-wise traffic insights.

🎯 Objectives
Detect vehicles (cars, trucks, buses, motorcycles, ambulances) from video streams
Perform class-wise traffic analysis
Convert unstructured video data into structured outputs
Visualize traffic patterns
⚙️ Features
✅ Custom-trained YOLOv8 model
✅ Video-based object detection
✅ Class-wise vehicle counting (frame-wise)
✅ CSV-based structured data generation
✅ Traffic pattern visualization
🧠 Tech Stack
Python
YOLOv8 (Ultralytics)
OpenCV
Pandas
Matplotlib
📊 Results
Achieved ~0.58 mAP (initial training run)
Generated class-wise traffic insights from video
Successfully processed real-world traffic footage
📂 Project Structure
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
├── README.md
▶️ How to Run
1. Clone the repository
git clone https://github.com/YOUR_USERNAME/smart-traffic-vision.git
cd smart-traffic-vision
2. Create virtual environment
python -m venv venv
venv\Scripts\activate
3. Install dependencies
pip install -r requirements.txt
4. Run the project
Open notebook or run scripts for:
model training
video inference
traffic analysis
📈 Future Improvements
Vehicle tracking for unique counting
Line-crossing traffic flow analysis
Real-time deployment using FastAPI
Traffic congestion detection system
