# Object_Counting_Project


# 🧮 Object Counting and Tracking Project

This project demonstrates **real-time object detection, tracking, and counting** using [YOLOv11](https://github.com/ultralytics/ultralytics) and OpenCV.  
It includes two main applications:

- 👤 **Pedestrian Counting** – detect and track people in a video
- 🚗 **Vehicle Line Counting** – detect and track vehicles, count how many cross predefined lines

---

## 📂 Project Structure

```
├── Pedestrian Counting.ipynb # pedestrian detection, tracking, scene counting
├── Vehicle Lines Counting.ipynb # vehicle tracking + line-based counting
├── requirements.txt # install dependencies
├── README.md # this file
└── resources.zip # contains YOLO weights + sample videos
```

---


## ⚙️ Installation

### 1. Create a conda environment (recommended)
```
conda create -n yolov11count python=3.9 -y
conda activate yolov11count
```
### 2. Clone the repo
```
git clone https://github.com/AAlaqeb/Object_Counting_and_Tracking_Project.git
cd Object_Counting_and_Tracking_Project
```
### 3. Install dependencies

#### Install PyTorch separately 
#### For GPU (CUDA 12.1, recommended)
```
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia -y
```
#### For CPU only:
```
pip install torch torchvision torchaudio
```
#### Install requirements
```
pip install -r requirements.txt
```
### 4. Download resources (YOLO weights + sample videos)

Download the zip file from Google Drive:
👉 [Google Drive – resources.zip](https://drive.google.com/drive/folders/1E6hmhKR9nbLMrpmqx9NM4lJca9bms_O6?usp=sharing)

Extract it into the repo root so the structure looks like:
```
Object_Counting_and_Tracking_Project/
│── yolo11m.pt
│── Pedestrians.mp4
├── indoor.mp4
└── vehicles.mp4
```

---
