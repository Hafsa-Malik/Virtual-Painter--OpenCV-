# Virtual-Painter--OpenCV-
Virtual Painter is a python based interactive application that utilizes computer vision techniques to detect the color of a marker held by the user. With the help of OpenCV, it allows real-time drawing on a webcam feed using the detected marker color.

## Features

- **Custom Marker Color Selection:** The colorPicker module enables users to select their desired marker color by adjusting the HSV (Hue, Saturation, Value) values using intuitive trackbars.

- **Real-time Drawing:** Once the marker color is selected, the virtualPainter module continuously analyzes the webcam feed. It tracks the movement of the marker and renders colored circles on the screen in real-time, providing an immersive virtual painting experience.

## Installation

1. Clone the repository `git clone https://github.com/Hafsa-Malik/Virtual-Painter--OpenCV.git` or directly download zip file.

2. Make sure you have OpenCV installed in main directory. If not cd to main directory and install `pip install opencv-python`


## Usage

1. Run the `colorPicker.py` script to select the marker color HSV values `python colorPicker.py`. Hold the marker infront of webcam and adjust trackbars until only the desired color is visible on the binary mask. Copy the HSV values and add them to `myColors` list as a new sub-list. Also add the corresponding BGR color which will be rendered on the canvas when these HSV values are detected in `myColorValues`.

2. Run the `virtualpainter.py` script `python colorPicker.py`. The webcam feed will open, displaying the real-time video stream.

3. Hold the marker in front of the camera and start drawing. The application will track the marker's movement and render colored circles on the screen accordingly.

4. Press the 'x' key to exit the application.

![outout](https://github.com/Hafsa-Malik/Virtual-Painter--OpenCV-/assets/76608263/585ae337-013f-4ada-93a5-64d40f3fd067)




## Requirements

- Python 3.x
- OpenCV

