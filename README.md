# Push-Up Counter using MediaPipe and OpenCV

This project utilizes the MediaPipe Pose model and OpenCV to create a push-up counter. It tracks the user's pose in real-time and counts push-ups based on the detected angles during the exercise.

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/push-up-counter.git
   cd push-up-counter
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script:**

   ```bash
   python push_up_counter.py
   ```

4. **Perform push-ups in front of your webcam, and the application will count them.**


## Configuration

- `max_angle`: Maximum angle considered for a push-up.
- `min_angle`: Minimum angle considered for a push-up.

## Features

- Real-time push-up counting.
- Visual feedback of the detected pose and angles.
- Stage tracking (up or down).

## Acknowledgments

- This project uses the [MediaPipe](https://github.com/google/mediapipe) library for pose detection.
- OpenCV is used for webcam video capture and image processing.
