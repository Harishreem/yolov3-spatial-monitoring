# Computer Vision: YOLOv3 Real-Time Spatial Monitoring System

A real-time video analytics and automated monitoring system engineered to detect individuals and calculate spatial distances between them. This project leverages deep learning object detection paired with geometric algorithms to flag proximity or safety violations dynamically.

## 📈 Performance & Key Results
* [cite_start]**Precision Tracking:** Built a visual alert system utilizing Non-Maximum Suppression (NMS) to eliminate redundant bounding boxes and flag safety violations accurately[cite: 43].
* [cite_start]**Baseline Accuracy:** Achieved a baseline **57% mean Average Precision (mAP)** on the live video stream tracking system[cite: 41, 44].

## 🛠️ System Architecture & Logic
* [cite_start]**Object Detection Pipeline:** Configured and deployed a `YOLOv3` framework specifically optimized to target and isolate the "person" class in live video feeds[cite: 41].
* [cite_start]**Spatial Logic Algorithm:** Engineered a custom tracking layer using **Centroid Tracking** and **Euclidean Distance** formulas to calculate pixel-to-real-world relative distances between individuals in real time[cite: 42].
* [cite_start]**Post-Processing:** Integrated NMS to handle overlapping bounding boxes, ensuring sharp, high-precision detection alerts[cite: 43].

## 🧰 Tech Stack
* **Language:** Python
* **Computer Vision Framework:** OpenCV
* **Model Architecture:** YOLOv3 (Darknet weights)
* **Mathematical Operations:** NumPy, SciPy
