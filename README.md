# Pose Estimation with OpenCV and MediaPipe

This project uses OpenCV and MediaPipe to perform real-time pose estimation on a video file. The script reads frames from a video, processes them to detect human poses, and draws the detected skeleton on the frames. Additionally, it calculates and displays the frames per second (FPS) for performance monitoring.

## Features

- Real-time pose estimation using MediaPipe
- Drawing detected skeleton on video frames
- FPS calculation and display

## Requirements

- Python 3.x
- OpenCV
- MediaPipe

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/pose-estimation-opencv-mediapipe.git
    cd pose-estimation-opencv-mediapipe
    ```

2. **Create a virtual environment (optional but recommended):**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```sh
    pip install opencv-python mediapipe
    ```

## Usage

1. **Place your video file in the project directory and rename it to `4.mp4`.**

2. **Run the script:**

    ```sh
    python pose_estimation.py
    ```

3. **Press `q` to exit the video display window.**



## Acknowledgements

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)




