**# 🚗 Vehicle Detection & Counting using YOLO + OpenCV

A real-time computer vision system for detecting, classifying, tracking, and counting vehicles in video streams using YOLO object detection and OpenCV. This project is intended for traffic monitoring, smart city analytics, and intelligent transportation systems.

---

## 📌 Overview

This system performs:
- Real-time vehicle detection  
- Vehicle classification (car, bus, truck, motorbike)  
- Persistent object ID tracking  
- Line-based directional vehicle counting  
- On-screen visual overlays  
- Output video recording (`output.mp4`)  

---

## 🔥 Demo Output  
🎥 Example output video:  
https://github.com/devparth19/Vehicle-Detection-Counting-using-YOLO-OpenCV/blob/main/output.mp4

---

## ✨ Key Features

- YOLO-based detection (Ultralytics YOLOv8n)
- GPU or CPU execution
- Real-time optimized
- Centroid-based vehicle tracking
- Counting logic using boundary crossing
- Input flexibility (video file or webcam)
- Results saved as annotated output video

---

## 🧠 Technologies Used

| Component | Purpose |
|----------|----------|
| Python | main implementation |
| YOLOv8n | vehicle object detection |
| OpenCV | drawing & video processing |
| NumPy | geometry & array handling |

📦 Output

- Program generates: output.mp4


## 🧩 Code Architecture

```bash
vehicle_detection_counting_yolo.py
│
├── YOLO model loading
├── CentroidTracker class
├── Video capture
├── YOLO inference per frame
├── Bounding box + classification
├── Centroid tracking per object
├── Crossing-line based counting
├── Visualization overlays
└── Output video writer (output.mp4)

