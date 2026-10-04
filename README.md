# OpenCV Human Recognition

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8.svg?logo=opencv)](https://opencv.org/)

> Real-time human detection and recognition system built with OpenCV — implementing face detection, body recognition, and motion tracking using classical and deep-learning computer vision techniques.

---

## Overview

This project explores human recognition in video streams and images using OpenCV. It demonstrates:
- **Face detection**: Haar cascade and/or DNN-based face detection
- **Body/pedestrian detection**: HOG descriptor with SVM classifier
- **Motion tracking**: Background subtraction for human presence detection
- Real-time inference on webcam and video file inputs

---

## Quickstart

### Prerequisites

- Python 3.9+
- OpenCV 4.x
- Webcam (for live demo) or video file

### Install & Run

```bash
git clone https://github.com/HiteshReddy2002/open-cv-human-recognition.git
cd open-cv-human-recognition

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install opencv-python opencv-contrib-python numpy

# Run on webcam (if entry point present):
python main.py --source 0

# Run on video file:
python main.py --source path/to/video.mp4
```

> **Note**: This repo is in early development. Entry point and code are being finalized. See the repo contents for current scripts.

---

## Roadmap

- [ ] YOLO-based real-time human detection
- [ ] Face recognition with deep embeddings (FaceNet/ArcFace)
- [ ] Multi-person tracking with DeepSORT
- [ ] Streamlit demo interface
- [ ] Docker containerization

---

## License

Distributed under the [GNU General Public License v3.0](LICENSE). Copyright (c) 2025 Hitesh Reddy Tippasani.
