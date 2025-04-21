# Facial Expression Recognition App

This project provides a PyQt-based application for detecting faces and recognizing facial expressions from various input sources. It supports:

- Live webcam input
- Single/multiple face images
- Video file input

The app detects one or more faces in the input, classifies the facial expressions, and visualizes the probability distribution of predicted emotions in real-time.

---

## Demo Video

You can preview the demo video here:  
[▶ Demo Video](https://github.com/user-attachments/assets/1dfa18b7-c0c6-4481-be6f-ad9f7e81ec6f)

---

## Features

- Face detection using FaceBoxes
- Expression recognition using a trained CNN model (`NLA_r18`)
- Real-time webcam mode
- Supports multiple faces in image input
- Expression distribution visualization using progress bars
- JSON output with predicted expression scores

---

## Files

| File | Description |
|------|-------------|
| `main_live_cam_video.py` | Run facial expression recognition in real-time from webcam input. Automatically exits if no face is detected for 10 consecutive frames. |
| `main_multi_face_image.py` | Run multi-face detection and expression analysis on a single image. |
| `main_single_face_image_video.py` | Run single-face expression recognition on a given image or video file. |

---

## Setup

### Environment

- Anaconda 23.7.2 recommended
- Python 3.8+
- Linux tested (Ubuntu-based systems)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your_username/Expression_app.git
   cd Expression_app

