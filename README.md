# ⚽ Football Player Tracking & Match Analysis using YOLOv5

An AI-powered computer vision project that detects, tracks, and analyzes football players, referees, and the ball from match videos using **YOLOv5**, **OpenCV**, and **Python**.

The project also estimates player speed, traveled distance, team ball possession, and camera movement, providing advanced match analytics through computer vision techniques.

---

## 📌 Overview

This project combines multiple computer vision algorithms to automatically analyze football matches.

It performs:

- 🎯 Real-time player, referee, and ball detection
- 📍 Multi-object tracking across video frames
- 👕 Team classification based on jersey colors
- ⚽ Ball possession estimation
- 🚶 Player speed calculation
- 📏 Distance traveled by each player
- 🎥 Camera motion estimation
- 🌍 Perspective transformation for real-world measurements

---

## ✨ Features

- Object Detection using **YOLOv5**
- Multi-object Tracking
- Team Assignment using **K-Means Clustering**
- Camera Motion Estimation using Optical Flow
- Perspective Transformation
- Ball Possession Statistics
- Speed Estimation
- Distance Measurement
- Match Analytics Visualization

---

## 🛠 Technologies

- Python
- YOLOv5
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Ultralytics
- Supervision

---

## 📂 Project Structure

```text
football-player-analysis/
│
├── camera_movement_estimator/
├── development_and_analysis/
├── models/
├── player_ball_assigner/
├── speed_and_distance_estimator/
├── team_assigner/
├── trackers/
├── training/
├── utils/
├── view_transformer/
├── yolov5/
│
├── main.py
├── yolo_inference.py
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/bilaldib/football-player-analysis.git
```

Move into the project directory

```bash
cd football-player-analysis
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate it

Windows

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run

```bash
python main.py
```

---

## 📸 Results

### Detection

- Football Players
- Referees
- Ball

### Tracking

- Persistent player IDs
- Ball tracking

### Analytics

- Speed estimation
- Distance traveled
- Team assignment
- Ball possession
- Camera motion compensation

---

## 📊 Example Output

> Add screenshots or GIFs inside the **assets/** folder.

Example:

```markdown
![Detection](assets/detection.png)

![Tracking](assets/tracking.gif)

![Analytics](assets/analytics.png)
```

---

## 📈 Future Improvements

- DeepSORT / ByteTrack integration
- Real-time webcam inference
- Player action recognition
- Automatic event detection
- Pass network analysis
- Expected Goals (xG)
- Tactical heatmaps
- Web dashboard using Streamlit

---

## 📄 Model

The trained weights (`best.pt`) are **not included** in this repository due to GitHub file size limitations.

Place your trained model inside:

```text
models/
```

before running the project.

---

## 🤝 Contributing

Contributions are welcome.

Feel free to fork this repository and submit a pull request.

---

## 👨‍💻 Author

**Bilal Dib**

Master's Student in Computer Science & Telecommunications

Faculty of Sciences – Mohammed V University (Rabat)

GitHub:
https://github.com/bilaldib

LinkedIn:
(Add your LinkedIn profile)

---

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.
