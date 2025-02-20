Color Detection using OpenCV
📌 Overview
This project uses OpenCV to detect and track colored objects in a video stream. It identifies objects of predefined colors (red, green, blue, yellow, and orange) in real-time using HSV color space and contour detection.

🚀 Features
Detects and tracks objects based on color.
Supports real-time video capture from a webcam or a provided video file.
Uses morphological transformations to refine detection.
Displays identified objects with bounding circles and labels.
🛠️ Technologies Used
Python
OpenCV
NumPy
Imutils
🔧 How to Run
Install the required dependencies:
bash
pip install opencv-python numpy imutils
Run the script with a webcam:
bash
python Color_detection.py
Run the script with a video file:
bash
python Color_detection.py --video path/to/video.mp4
Press 'q' to exit the application.
📌 Configuration
Modify the lower and upper dictionaries in the script to adjust HSV color ranges for detection.
Adjust the buffer size for tracking optimization.
📷 Output
The program displays the video feed with detected objects highlighted using colored circles and labels.
