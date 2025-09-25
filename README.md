# Object_Counting_Project


# 🧮 Object Counting and Tracking Project

This project demonstrates **real-time object detection, tracking, and counting** using [YOLOv11](https://github.com/ultralytics/ultralytics) and OpenCV.  
It includes two main applications:

- 👤 **Pedestrian Counting** – detect and track people in a video
- 🚗 **Vehicle Line Counting** – detect and track vehicles, count how many cross predefined lines

---

## 📂 Project Structure


├── Pedestrian Counting.ipynb # pedestrian detection, tracking, scene counting

├── Vehicle Lines Counting.ipynb # vehicle tracking + line-based counting

├── requirements.txt # install dependencies

├── README.md # this file

└── resources.zip # contains YOLO weights + sample videos


---

## 📥 Resources (YOLO Weights + Videos)

All required files (YOLOv11 weights and sample videos) are packed into a single zip.  
Download it here:  

👉 [Google Drive – resources.zip](https://drive.google.com/drive/folders/1E6hmhKR9nbLMrpmqx9NM4lJca9bms_O6?usp=sharing)

After downloading, extract it into the repo root:

Object_Counting_and_Tracking_Project/
```
│── yolo11m.pt
│── Pedestrians.mp4
├── indoor.mp4
└── vehicles.mp4
```

## ⚙️ Installation

### 1. Create a conda environment (recommended)
```bash
conda create -n yolov11count python=3.9 -y
conda activate yolov11count
```
-
2. Install dependencies
pip install -r requirements.txt

3. Clone the repo
git clone https://github.com/AAlaqeb/Object_Counting_and_Tracking_Project.git
cd Object_Counting_and_Tracking_Project

4. Download resources (YOLO weights + sample videos)

Download the zip file from Google Drive:
👉 resources.zip

Extract it into the repo root so the structure looks like:

Object_Counting_and_Tracking_Project/
│── yolo11m.pt
│── sample_videos/
│    ├── people2.mp4
│    └── traffic.mp4


---
