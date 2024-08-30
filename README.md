# Object Detection Application

This is a simple object detection application built using Python, OpenCV, Streamlit, and MediaPipe. The application allows users to upload an image, detect objects within the image using a pre-trained TensorFlow Lite model, and visualize the detection results.

## Features

- **Object Detection**: Detects objects in an uploaded image using a TensorFlow Lite model.
- **Visualization**: Draws bounding boxes around detected objects and labels them with their category name and detection probability.
- **Streamlit Interface**: Provides a user-friendly interface for uploading images and displaying detection results.

## Requirements

- Python 3.x
- Streamlit
- OpenCV
- NumPy
- MediaPipe

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/object-detection-app.git
   cd object-detection-app
Install the required Python packages:

bash
pip install streamlit opencv-python-headless numpy mediapipe

Download the TensorFlow Lite model (efficientdet_lite0.tflite) and place it in the appropriate directory. You can download the model from TensorFlow Hub.

