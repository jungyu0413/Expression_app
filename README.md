# Facial Expression Recognition App

This is a PyQt5-based desktop application that integrates **face detection** and **facial expression recognition** using deep learning models. It supports the following input modes:

- **Live Camera Streaming** (real-time expression inference)
- **Image Files** (single or multiple faces)
- **Video Files** (single-face inference)

The app detects faces in the input, performs expression classification, and visualizes the probability distribution of seven emotions in a clean and interactive UI.

## Features

- Multi-face detection and expression recognition on static images
- Single-face recognition from images or video files
- Real-time expression inference via live webcam
- Softmax-based expression probability visualization
- Clean Qt interface with dynamic layout scaling

## Project Structure

| File | Description |
|------|-------------|
| `main_live_cam_video.py` | Real-time facial expression recognition from webcam stream |
| `main_multi_face_image.py` | Expression recognition for multiple faces in a single image |
| `main_single_face_image_video.py` | Single-face recognition from static image or video file |

## Sample Video

Sample video available here:  
[🔗 Download Sample Video](https://github.com/user-attachments/assets/afec4345-c458-47d2-ad89-3322116f4dc7)

## Environment

- Python version managed via [Anaconda 23.7.2](https://www.anaconda.com)
- Dependencies listed in `requirements.txt`

To install required packages:

```bash
pip install -r requirements.txt
