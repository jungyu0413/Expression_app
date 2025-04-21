# Expression Recognition Application

This repository provides a facial expression recognition application that leverages face detection and emotion classification models. It supports input from single/multiple face images, video files, and real-time webcam streams. The application detects faces and visualizes the probability distribution of predicted expressions.

## Features
- Face detection for single and multiple faces
- Expression recognition with probability visualization
- Supports image, video, and real-time camera input
- Auto-close webcam if no face is detected for 10 frames
- Clean PyQt5 GUI with real-time updates

## Demo Video
<video src="[https://github.com/user-attachments/assets/1dfa18b7-c0c6-4481-be6f-ad9f7e81ec6f](https://github.com/user-attachments/assets/afec4345-c458-47d2-ad89-3322116f4dc7)" controls width="600">
  Your browser does not support the video tag.
</video>

## File Descriptions
- `main_live_cam_video.py`: Runs live webcam input for real-time expression recognition. Auto-terminates if no face is detected for 10 consecutive frames.
- `main_single_face_image_video.py`: Allows user to load an image or video. Detects and analyzes the main face.
- `main_multi_face_image.py`: Loads a single image and detects expressions for all visible faces.

## Requirements
- Python (tested with Anaconda 23.7.2)
- Install all dependencies:

```bash
pip install -r requirements.txt
```

## Usage

### Run with webcam (real-time)
```bash
python main_live_cam_video.py
```
- Detects expressions continuously using your system camera.
- Terminates automatically if no face is detected for 10 frames.

### Run on a single image or video file
```bash
python main_single_face_image_video.py
```
- Opens a dialog to load a static image or video.
- Supports face detection and expression recognition on the main face.

### Run on an image with multiple faces
```bash
python main_multi_face_image.py
```
- Detects and displays expressions for all visible faces in the image.

---

Feel free to clone the repository, explore the GUI, and customize for your specific use-case.

