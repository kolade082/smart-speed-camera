# Smart Speed Camera System for Pedestrian Safety

## Overview

This project is a Smart Speed Camera System designed to enhance pedestrian safety on the University of Northampton campus. The system leverages computer vision techniques to detect and monitor vehicle speeds in real-time, providing an automated solution for traffic management and safety enforcement.

## Features

- **Real-Time Video Capture**: Live video feed from connected cameras.
- **Object Detection**: Utilizes YOLOv3 for detecting vehicles (cars, trucks, buses).
- **Speed Calculation**: Calculates the speed of detected vehicles using a fixed distance method.
- **Video Recording**: Allows recording of live video feeds for later analysis.
- **Frame Capture**: Captures individual frames from the video feed.
- **Image Stitching**: Stitches multiple frames to create panoramic views.
- **User-Friendly Interface**: Built with Tkinter for easy interaction and control.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/kolade082/smart-speed-camera.git
   cd media-tech
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Application**:
   ```bash
   python main.py
   ```

## Usage

1. **Start the Application**: Run the script to launch the GUI.
2. **Go Live**: Click the "Go Live" button to start the live video feed.
3. **Select Video**: Use the "Select Video" button to load a pre-recorded video.
4. **Control Playback**: Use the "Play", "Pause/Resume", and "Stop" buttons to control video playback.
5. **Capture Frames**: Click "Capture Frame" to save individual frames.
6. **Start/Stop Recording**: Use the "Start Recording" and "Stop Recording" buttons to record live video.
7. **Stitch Frames**: Click "Stitch Frames" to create a panoramic image from captured frames.

## Dependencies

- Python 3.x
- Tkinter
- OpenCV (`cv2`)
- cvlib
- NumPy
- PIL (Pillow)
