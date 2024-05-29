# Real-Time Face, Eyes, and Smile Detection

![Face Detection Example](https://github.com/Arsalanzabeeb786/Face-Detection-with-OpenCV/blob/main/video_screenshot.png)

This project demonstrates how to use OpenCV, a powerful computer vision library, to perform real-time detection of faces, eyes, and smiles via a webcam. The detection results are visualized by drawing rectangles around the detected features directly on the video feed.

## Key Features

- **Real-Time Detection:** Utilizes the webcam to detect and display faces, eyes, and smiles in real-time.
- **Haar Cascade Classifiers:** Uses pre-trained Haar Cascade classifiers for accurate detection of facial features:
  - `haarcascade_frontalface_default.xml`: Detects faces.
  - `haarcascade_eye.xml`: Detects eyes within detected faces.
  - `haarcascade_smile.xml`: Detects smiles within detected faces.
- **Visualization:** Draws colored rectangles around detected features:
  - Blue rectangles for faces.
  - Green rectangles for eyes.
  - Red rectangles for smiles.

## Requirements

- Python 3.10 and above
- OpenCV
- Jupyter Lab (for running the code in a notebook environment)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Arsalanzabeeb786/Face-Detection-with-OpenCV.git
   cd face-detection
