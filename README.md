# Real-Time-Sign-Language-Detection-using-TensorFlow-Object-Detection-API-

Real-Time Sign Language Detection using TensorFlow Object Detection API

This project demonstrates a real-time sign language recognition system built using the TensorFlow Object Detection API. It detects hand gestures representing letters or signs from sign language via live webcam input.

##  Overview

With the rise of deep learning and computer vision, real-time gesture recognition has become increasingly achievable on consumer hardware. This project trains a custom object detection model (SSD MobileNet V2) to identify hand signs and enables real-time detection using a webcam feed.
## 📁 Project Structure

Real-Time-Sign-Language-Detection/ │ ├── annotations/ │ ├── label_map.pbtxt # Maps numeric labels to sign classes │ ├── train.record # TFRecord for training data │ └── test.record # TFRecord for test data │ ├── images/ │ ├── train/ # Training images with XML annotations │ └── test/ # Testing images with XML annotations │ ├── models/ │ └── my_ssd_mobnet/ # Custom model folder │ ├── checkpoint/ # Checkpoint files from training │ └── pipeline.config # Configuration file for model training │ ├── pre-trained-models/ │ └── ssd_mobilenet_v2/ # Base model from TensorFlow Model Zoo │ ├── exported-models/ │ └── my_model/ # Trained model exported for inference │ └── saved_model/ # TensorFlow SavedModel format │ ├── scripts/ │ ├── generate_tfrecord.py # Converts XML annotations to TFRecord │ └── utils.py # Utility functions (optional) │ ├── 2. Training and Detection.ipynb # Main notebook for training and detection ├── README.md # Project documentation └── requirements.txt # Python dependencies

## 📦 Requirements

- Python 3.7+
- TensorFlow 2.x
- TensorFlow Object Detection API
- OpenCV
- Protobuf
- Pandas, lxml, matplotlib
