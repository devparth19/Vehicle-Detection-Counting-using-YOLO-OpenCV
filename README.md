# Vehicle Detection & Counting using YOLO + OpenCV

This project performs real-time vehicle detection, classification, and counting using YOLO object detection and OpenCV. Vehicles are tracked as they cross a virtual detection boundary, and results are displayed and saved into an output video.

---

## 🔗 GitHub Repository

🔗 Project Link: https://github.com/devparth19/Vehicle-Detection-Counting-using-YOLO-OpenCV  
🎥 Output Video (output.mp4):  
https://github.com/devparth19/Vehicle-Detection-Counting-using-YOLO-OpenCV/blob/main/output.mp4

---

## ✨ Features

- Real-time vehicle detection  
- Classification of:
  - car  
  - bus  
  - motorbike  
  - truck  
- Object tracking using a centroid-based tracker  
- Vehicle counting based on crossing a detection line  
- Saves processed annotated video as `output.mp4`  
- Works with:
  - uploaded video file
  - live webcam input  

---

## 🧠 Model Used

- **YOLOv8n (Ultralytics)**  
- Pretrained on COCO dataset (80 classes)  
- Lightweight + fast for real-time  

---

## 🛠️ Installation

Make sure Python 3.8+ is installed.

Install dependencies:
python vehicle_detection_counting_yolo.py

📦 Output

While running, the program:

✔ draws bounding boxes
✔ labels each vehicle type
✔ assigns a unique ID to each vehicle
✔ counts number of vehicles crossing the line

And generates:
output.mp4


```bash
pip install ultralytics opencv-python numpy
