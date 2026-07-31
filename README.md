# ⚽ AI Football Player Tracking & Match Analysis

<div align="center">

# AI-Powered Football Analytics using Computer Vision

**Bachelor's Final Year Project (2024–2025)**

Faculty of Sciences – Mohammed V University in Rabat

Bachelor's Degree in Physics  
**Electronics, Computer Science & Automation**

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![YOLOv5](https://img.shields.io/badge/YOLOv5-Computer%20Vision-red)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![GitHub](https://img.shields.io/github/stars/bilaldib/football-player-analysis)

</div>

---

# 📖 Project Overview

This project was developed as my **Bachelor's Final Year Project (2024–2025)** for the Bachelor's Degree in **Physics – Electronics, Computer Science & Automation** at the **Faculty of Sciences, Mohammed V University in Rabat**.

The objective was to design and implement an intelligent football match analysis system using **Computer Vision**, **Deep Learning**, and **Artificial Intelligence**.

The application automatically detects and tracks football players, referees, and the ball while generating advanced match analytics such as:

- Player tracking
- Ball tracking
- Team identification
- Ball possession estimation
- Camera motion compensation
- Perspective transformation
- Speed estimation
- Distance covered by each player

This project combines modern AI techniques with practical sports analytics to demonstrate real-world applications of deep learning and computer vision.

---

# 🎯 Main Features

- ⚽ Football player detection
- 🥅 Ball detection
- 👨‍⚖️ Referee detection
- 🎯 Multi-object tracking
- 👕 Team classification using K-Means clustering
- 📊 Ball possession estimation
- 🎥 Camera motion estimation
- 🌍 Perspective transformation
- 🚀 Player speed estimation
- 📏 Distance calculation
- 📈 Football match analytics

---

# 🛠️ Technologies

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| AI Model | YOLOv5 |
| Computer Vision | OpenCV |
| Machine Learning | Scikit-Learn |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| Version Control | Git & GitHub |

---

# 🏗️ System Architecture

```text
Football Video
      │
      ▼
YOLOv5 Object Detection
      │
      ▼
Multi-Object Tracking
      │
      ▼
Team Classification
      │
      ▼
Camera Motion Estimation
      │
      ▼
Perspective Transformation
      │
      ▼
Speed & Distance Estimation
      │
      ▼
Match Analytics Dashboard
```

---

# 🚀 Installation

```bash
git clone https://github.com/bilaldib/football-player-analysis.git

cd football-player-analysis

python -m venv .venv

# Windows
.venv\Scripts\activate

# Linux / macOS
source .venv/bin/activate

pip install -r requirements.txt
```

---

# ▶️ Run

```bash
python main.py
```

---

# 📂 Repository Structure

```text
football-player-analysis
│
├── camera_movement_estimator
├── player_ball_assigner
├── speed_and_distance_estimator
├── team_assigner
├── trackers
├── utils
├── view_transformer
├── yolov5
├── main.py
└── yolo_inference.py
```

---

# 📸 Results

The application is capable of:

- Detecting players, referees and the ball
- Tracking every object throughout the match
- Assigning players to their respective teams
- Estimating player speed
- Measuring distance covered
- Computing ball possession statistics

> Screenshots and demo GIFs will be added in the `assets/` directory.

---

# 📄 Trained Model

The trained model (`best.pt`) is not included in this repository because of GitHub file size limitations.

Download the model and place it inside the `models/` directory before running the application.

---

# 👨‍🏫 Academic Supervision

**Supervisor**

**Dr. Hassan Roukhe**

Faculty of Sciences – Mohammed V University in Rabat

**Co-Supervisor**

**Dr. Khalid ELAMRAOUI**

Faculty of Sciences – Mohammed V University in Rabat

---

# 👨‍💻 Author

## Bilal Dib

Master's Student in Computer Science & Telecommunications

Faculty of Sciences – Mohammed V University in Rabat

- **GitHub:** https://github.com/bilaldib
- **LinkedIn:** https://www.linkedin.com/in/bilal-dib-354796376/

---

# ⭐ Support

If you find this repository useful, please consider giving it a ⭐.
