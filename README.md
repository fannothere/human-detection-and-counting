# Human Detection and Counting using OpenCV

This project demonstrates how to detect and count humans in real-time video or video files using Python and OpenCV. The human detection is performed using the HOG (Histogram of Oriented Gradients) descriptor with a pre-trained SVM model provided by OpenCV.

## Features
<ul>
<li>Real-time human detection: Detects humans in live video streams (webcam) or from video files.</li>
<li>Human counting: Counts the number of humans detected in each frame and displays the count.</li>
</ul>

## Prerequisites
Before running the program, ensure you have the following installed:
<ol>
<li>Python (version 3.6 or above)</li>
<li>Python (version 3.6 or above)</li>OpenCV: The OpenCV Python library for image and video processing.
</ol>

## Installing OpenCV
You can install OpenCV using pip:
```
pip install opencv-python
```
## How to Run
<ol>
<li>Clone the repository or download the Python script.</li>
<li>Ensure OpenCV is installed using the command pip install opencv-python.</li>
Run the Python script:
  
```
python main.py
```
<li>The program will start capturing video from your webcam by default. To use a video file, replace the webcam source with the path to the video file (see Code Overview).</li>

<li>The program will display the video feed with rectangles around detected humans and show the human count. Press q to quit the program.</li>

</ol>
