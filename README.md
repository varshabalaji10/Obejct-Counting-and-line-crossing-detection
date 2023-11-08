# Object Counting and Line Crossing Detection
This Python script is designed for object counting and line crossing detection in video frames. It utilizes the OpenCV library for video processing and computer vision tasks.

### Prerequisites
Before running the script, make sure you have the following libraries installed:

OpenCV
NumPy
Tkinter (for file dialog)
Python 3.x
You can install OpenCV and NumPy using pip:
```bash
pip install opencv-python numpy
```
### Usage
Run the script.

A file dialog will open, allowing you to select a video file for processing.

The script captures the video and processes each frame for object detection.

It identifies and counts objects that cross specific lines within the frame.

The number of objects crossing above and below the lines is displayed on the video frame.

The processed frames are recorded and saved as an output video file named 'test_output.avi'.

Press the 'Esc' key to stop the script and close the video windows.

### Customization
You can customize the script by modifying the following parameters:

OffsetRefLines: Adjust this value to control the position of the reference lines for object counting.

history and backgroundRatio: If you use a different background subtractor, you can adjust these parameters.

line1 and line2 functions: Modify these functions to change the logic for determining if an object has crossed a line.

### Example
The script is useful for monitoring entry and exit points, tracking object movements, and counting objects that cross specific lines. You can use it in various applications, such as traffic analysis, people counting, and more.

Enjoy using this object counting and line crossing detection script!
