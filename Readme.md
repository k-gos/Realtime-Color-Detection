# color-detection-opencv

Color detection with Python and OpenCV !

This Python script uses OpenCV to perform real-time color detection and draws bounding boxes around specific colors in a live video feed. It is designed to detect the colors yellow, red, green, and blue.

Prerequisites
Python 3.x
OpenCV (pip install opencv-python)
NumPy (pip install numpy)
Pillow (pip install pillow)

Usage:
Install dependencies:

pip install -r requirements.txt

Run the script:

python color_detection.py

Press 'q' to exit the program.

How it Works
The script captures video from the default camera, converts each frame to the HSV color space, and then detects the colors yellow, red, green, and blue using specified HSV color ranges. Bounding boxes are drawn around the detected regions, and the color name is displayed above each box.

Configuration
The colors dictionary in the script defines the BGR values for yellow, red, green, and blue. You can modify these values or add more colors as needed.
