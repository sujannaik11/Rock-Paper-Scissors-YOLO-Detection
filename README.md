# Rock Paper Scissors Detection Using YOLO

## Overview
This project uses a custom-trained YOLO object detection model to recognize Rock, Paper, and Scissors hand gestures in real time through a webcam.

## Features
- Real-time webcam detection
- Recognizes Rock, Paper, and Scissors
- Displays bounding boxes and class labels
- Shows confidence scores for detected gestures

## Technologies Used
- Python
- YOLO (Ultralytics)
- OpenCV

## Project Structure
```text
Rock-Paper-Scissors-YOLO-Detection/
├── detect_webcam.py
├── best.pt
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation
Install the required libraries:

```bash
pip install -r requirements.txt
```

## Run the Project
Ensure that `best.pt` and `detect_webcam.py` are in the same directory.

```bash
python detect_webcam.py
```

Show a Rock, Paper, or Scissors gesture in front of your webcam. Press `q` to exit.

## Model
The project uses a custom-trained model based on the Rock-Paper-Scissors dataset.

## Future Improvements
- Improve detection accuracy under different lighting conditions.
- Support multiple hands in a single frame.
- Build a graphical user interface.
