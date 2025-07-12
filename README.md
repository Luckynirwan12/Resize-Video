# 🎞️ Video Resizer using OpenCV (Reduce Size by 50%)
This Python script resizes a colored video to 50% of its original width and height using the OpenCV library. It processes the video frame by frame, resizes each frame, and saves the result as a new video file.

## ✅ Features
- 📏 Reduces video resolution by exactly 50%

- 🎥 Supports common video formats like `.mp4`, `.avi`

- ⚙️ Maintains original frame rate and duration

- 💾 Saves output as a new video without modifying the original

## 🛠️ Requirements
- Python 3.x

- OpenCV (cv2)

- Install with:

      pip install opencv-python

## 🚀 How It Works
1. Loads the input video using `cv2.VideoCapture()`

2. Retrieves video properties (resolution, frame rate)

3. Calculates new dimensions (width/2, height/2)

4. Resizes each frame using `cv2.resize()`

5. Writes the resized frames to a new video file using `cv2.VideoWriter()`

## 🧪 How to Use
1. Place your input video file (e.g., `input_video.mp4`) in the project folder.

2. Run the script:

       python resize_video.py

3. The resized video will be saved as:

       resized_video.mp4
