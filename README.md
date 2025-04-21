# Facial Expression Recognition App

This PyQt5-based desktop application performs real-time and offline facial expression recognition using deep learning models. It supports:

- Real-time webcam input
- Static image input (single or multiple faces)
- Video file input (single face)

The app detects faces, predicts expressions, and visualizes the softmax probability distribution of seven emotions with a user-friendly interface.

## Project Structure

| File | Description |
|------|-------------|
| `main_live_cam_video.py` | Real-time facial expression recognition using webcam |
| `main_multi_face_image.py` | Recognizes expressions from multiple faces in an image |
| `main_single_face_image_video.py` | Recognizes expressions from a single face in an image or video |

## Sample Video

You can preview a demo video here:  
[https://github.com/user-attachments/assets/afec4345-c458-47d2-ad89-3322116f4dc7](https://github.com/user-attachments/assets/afec4345-c458-47d2-ad89-3322116f4dc7)

*(Click to open in browser. GitHub will render the video inline.)*

## Environment

- Python environment: **Anaconda 23.7.2**
- Dependencies: listed in `requirements.txt`

To install required packages:

```bash
pip install -r requirements.txt

