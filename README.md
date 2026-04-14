# 🧠 PCB Defect Detection using YOLOv8

## 📌 Project Overview

This project focuses on the automatic detection of defects in Printed Circuit Boards (PCBs) using deep learning techniques.
The goal is to replace traditional manual inspection methods with a faster, more accurate, and scalable AI-based solution.

The system leverages the YOLOv8 model to detect and classify multiple types of PCB defects in real-time.

---

## 🎯 Objectives

* Automate PCB defect detection using computer vision
* Improve accuracy and reduce human inspection errors
* Enable real-time detection for industrial applications
* Prepare deployment on embedded systems (e.g., Raspberry Pi)

---

## 🛠️ Technologies Used

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* NumPy
* Google Colab (training environment)

---

## 📊 Dataset Description

The dataset used in this project consists of labeled PCB images containing different types of defects.

### 🔍 Defect Classes:

* Missing Hole
* Mouse Bite
* Open Circuit
* Short Circuit
* Spur
* Spurious Copper

Each image is annotated using bounding boxes for object detection tasks.

⚠️ **Note:**
Due to size limitations, the dataset is not included in this repository.

👉 You can access the dataset here:
**https://drive.google.com/drive/folders/1dk0VrewCPp7_UJdkyxS1fzcwGFg64_eo**

---

## 📂 Project Structure

```
pcb-defect-detection/
│── notebook.ipynb        # Training and testing notebook
│── images/               # Sample results (optional)
│── README.md
│── .gitignore
```

---

## 🚀 How to Run the Project

### 1. Install dependencies

```bash
pip install ultralytics opencv-python numpy
```

### 2. Train the model

```bash
yolo detect train data=data.yaml model=yolov8n.pt epochs=50
```

### 3. Run inference

```bash
yolo detect predict model=best.pt source=images/
```

---

## 📈 Results

(Add your real results here)

* mAP@0.5: XX%
* Precision: XX%
* Recall: XX%

---

## 🔍 Sample Results

(Add some detection images here)

Example:

```
images/result1.jpg
images/result2.jpg
```

---

## 🧠 Future Improvements

* Improve model accuracy with more data
* Optimize inference speed for real-time deployment
* Deploy the system on Raspberry Pi
* Integrate with industrial monitoring systems

---

## 👩‍💻 Author

**Balkis Belghouthi**
Engineering Student in Electronics & Nanotechnology
Passionate about AI, Computer Vision, and Embedded Systems

---

## 📬 Contact

Feel free to reach out for collaboration, questions, or opportunities.
