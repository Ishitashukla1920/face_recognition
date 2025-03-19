# Face Recognition System

## Overview
This project implements a face recognition system using OpenCV and LBPH (Local Binary Patterns Histograms) in Python. It detects faces from images, trains a model using a provided dataset, and recognizes faces from new images. This implementation runs on Google Colab and supports uploading images for training and recognition.

## Features
- Face detection using OpenCV's Haar cascades
- Face recognition using LBPH Face Recognizer
- Model training with a single or multiple images
- Face recognition from uploaded images
- Supports Google Colab environment
- CSV dataset integration
- Model and labels stored for future recognition

## Installation
Run the following command to install dependencies in Google Colab:
```bash
!pip install opencv-contrib-python numpy
```

## Dataset Preparation
1. Upload your CSV dataset containing image paths and labels.
2. Ensure images are properly formatted and stored in the correct directory.

## Usage
### 1️⃣ Train the Model with a Single Image
```python
train_single_image()
```
- Upload an image when prompted.
- Enter your name for labeling.
- The model is trained and saved.

### 2️⃣ Recognize a Face
```python
recognize_face()
```
- Upload an image for recognition.
- The system predicts the person's name with confidence score.

## Model Saving & Loading
- The trained model is saved as `face_model.xml`.
- Labels are stored in `face_labels.pkl`.

## Uploading to GitHub
To upload trained files to GitHub:
```bash
!git remote set-url origin https://your-github-token@github.com/your-username/your-repository.git
!git push origin main
```

## Requirements
- Python 3
- OpenCV
- NumPy
- Google Colab (for cloud execution)

## Future Improvements
- Support for real-time face recognition
- UI for easy interaction
- Deep learning-based recognition (FaceNet, Dlib, etc.)

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss the proposed change.

## License
This project is open-source under the MIT License.


