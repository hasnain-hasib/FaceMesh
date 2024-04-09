# Real-time Face Mesh Detection using MediaPipe

This Python script demonstrates real-time face mesh detection using the MediaPipe library. It captures video from the webcam, processes it to detect facial landmarks, and overlays the detected landmarks on the video stream.

## Prerequisites

Before running the script, ensure you have the following dependencies installed:

- Python 3.x
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)

## Usage

1. Clone the repository or download the script.
2. Ensure your webcam is connected and accessible.
3. Run the script using the command `python face_mesh_detection.py`.
4. The script will open a window displaying the webcam feed with facial landmarks overlaid.
5. Press 'q' to exit the script.

## Script Overview

- The script imports the necessary libraries: `cv2` for video capture and visualization, and `mediapipe` for face mesh detection.
- It initializes the MediaPipe Face Mesh model.
- The script then captures video from the webcam frame by frame.
- It processes each frame to detect facial landmarks using the Face Mesh model.
- Detected landmarks are overlaid on the video frame using OpenCV.
- Pressing 'q' during execution quits the script.

## Acknowledgments

- This script utilizes the MediaPipe library for real-time face mesh detection.
- Special thanks to the OpenCV community for providing robust computer vision tools.
  
## References

- [MediaPipe](https://mediapipe.dev/)
- [OpenCV](https://opencv.org/)

Feel free to modify and extend this script according to your requirements! If you have any questions or suggestions, please feel free to reach out.
