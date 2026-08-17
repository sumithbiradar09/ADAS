# AI-Based Traffic Sign Recognition System

A Computer Vision and Deep Learning-Based Intelligent Driver Assistance System for Real-Time Traffic Sign Detection and Recognition.

---

## 📌 Project Overview

The **AI-Based Traffic Sign Recognition System** is designed to automatically detect and classify traffic signs from road images or video frames. The system uses Computer Vision and Deep Learning techniques to identify important traffic signs such as speed limits, stop signs, no-entry signs, pedestrian crossings, warning signs, and directional signs.

The proposed system is intended to support **Advanced Driver Assistance Systems (ADAS)** by providing timely information and alerts to drivers. It follows a pipeline of image acquisition, preprocessing, traffic-sign detection, sign classification, result display, and driver alert generation.

---

## 🎯 Key Objectives

* **Traffic Sign Detection:** Build a computer vision pipeline capable of locating traffic signs from road images or video frames.
* **Traffic Sign Classification:** Train and implement a deep learning model to accurately classify different traffic-sign categories.
* **Real-Time Recognition:** Develop a recognition module that can process continuous video frames and provide quick predictions.
* **Driver Assistance:** Display the detected traffic sign, its category, and its meaning to assist the driver.
* **Performance Evaluation:** Evaluate recognition performance under different road, lighting, and visibility conditions.
* **Future ADAS Integration:** Provide a foundation for integration with other ADAS functions such as lane detection, traffic-light recognition, and collision warning.

---

## 📄 Abstract

Traffic signs are an important part of road safety because they guide drivers and communicate rules, warnings, and important information. In busy roads, unfamiliar areas, or poor visibility, drivers may sometimes miss a sign or fail to recognize it quickly. This project proposes an **AI-based Traffic Sign Recognition System** that can automatically identify traffic signs from road images or video frames. Using Computer Vision and Deep Learning, the system detects the sign, classifies it into the correct category, and displays its meaning to the driver. The main goal is to provide a simple and useful driver-assistance system that can recognize traffic signs quickly and support safer driving. The system can later be integrated with real-time vehicle cameras and other ADAS features to improve road safety and driving awareness.

---

## 📊 Dataset

* **Dataset Overview:**
  * **GTSRB (German Traffic Sign Recognition Benchmark):** A widely used traffic-sign recognition benchmark containing more than 50,000 images across 43 traffic-sign classes.
  * **Traffic Sign Images:** Road images can be used for training, validation, and testing the recognition model.
  * **Video Frames:** Continuous road-video frames can be used to demonstrate real-time detection and recognition.

* **Dataset Link:**
  * [GTSRB Official Benchmark](https://benchmark.ini.rub.de/)

---

## ⚙️ System Workflow

```text
START
   ↓
Capture Road Image / Video Frame
   ↓
Image Preprocessing
   ↓
Detect Traffic Sign
   ↓
Extract Sign Region
   ↓
Deep Learning Classification
   ↓
Identify Traffic Sign
   ↓
Display Sign + Meaning
   ↓
Provide Driver Alert
   ↓
Process Next Frame
```

---

## 🧠 Technologies Used

* **Python** — Main programming language
* **OpenCV** — Image and video processing
* **Deep Learning / CNN** — Traffic-sign classification
* **YOLO** — Traffic-sign object detection
* **NumPy** — Numerical processing
* **Matplotlib** — Visualization
* **TensorFlow / PyTorch** — Model training and inference
* **Google Colab / VS Code** — Development environment

---

## 🔬 Research & References

* **Man vs. computer: Benchmarking machine learning algorithms for traffic sign recognition** — [ScienceDirect Paper](https://www.sciencedirect.com/science/article/pii/S0893608012000457)

* **Traffic sign recognition based on deep learning** — [Springer Paper](https://link.springer.com/article/10.1007/s11042-022-12163-0)

* **An Improved Traffic Sign Detection and Recognition Deep Model Based on YOLOv5** — [IEEE Paper](https://doi.org/10.1109/ACCESS.2023.3281551)

* **Traffic Sign Detection and Recognition Using YOLO Object Detection Algorithm: A Systematic Review** — [MDPI Paper](https://www.mdpi.com/2227-7390/12/2/297)

* **Efficient Traffic Sign Recognition Using YOLO for Intelligent Transport Systems** — [Scientific Reports Paper](https://www.nature.com/articles/s41598-025-98111-y)

---

## ⚠️ Limitations

* Traffic signs may be difficult to recognize when they are partially blocked or damaged.
* Small traffic signs can reduce detection accuracy.
* Rain, fog, shadows, glare, and low-light conditions can affect recognition performance.
* Deep learning models require sufficiently large and accurately labelled datasets.
* Real-time video processing may require significant computational resources.
* Performance on controlled datasets may not always represent complex real-world driving conditions.

---

## 🚀 Future Scope

* Real-time traffic sign recognition using vehicle-mounted cameras.
* Integration with lane detection and traffic-light recognition.
* Explainable AI (XAI) for more transparent traffic-sign predictions.
* Improved recognition under rain, fog, low light, blur, glare, and partial occlusion.
* Edge-AI deployment for low-latency processing inside vehicles.
* Integration with GPS, LiDAR, radar, and other sensor data.
* Integration with larger ADAS and autonomous-driving systems.

---

## 👥 Team Members

| Name | Roll No |
| :--- | :--- |
| **Ch. Yaswanth Sai** | 2420090154 |
| **B. Sumith** | 2420030696 |
| **K. Shruthik Reddy** | 2420030247 |

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* mAP (for object detection)
* Inference Time / FPS

---

## 📜 Project Status

**Academic Engineering Capstone Project — Traffic Sign Recognition / ADAS**

The project focuses on developing and evaluating a computer-vision and deep-learning-based traffic-sign recognition system that can later be extended toward real-time intelligent driver assistance.
