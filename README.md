# PFA-II : Smart Car Remote
Repo for our PFA II code files and folders.
This is an end of second year academic project, elaborated by Nour Ben Sghaier and Souha Ghabri, and supervised by Mr Marwen Kermani.

## Introduction
The aim of this project is to provide a more autonounous lifestyle to drivers by adding more security to their cars and turning various features to mobile controlled and supervised, using a mobile application.

Using a Raspberry Pi and a camera module for computer vision with OpenCV (and TensorFlow Lite). 
Computer vision based on cameras is very powerful and will bring a project to the next level. 
This allows to track complicated objects that would otherwise not be possible with other type of sensors (infrared, ultrasonic, LiDAR, etc).

Note the code is based on Python and OpenCV meaning it is cross-platform. 
It can be run on other Linux-based platforms as well, e.g. x86/x64 PC, IPC, Jetson, Banana Pi, LattaPanda, BeagleBoard, etc.

## Packages requirement

This project is dependent on the following packages:

- Python >= 3.5
- OpenCV-Python
- OpenCV-Contrib-Python
- NumPy
- SciPy
- Matplotlib

## Hardware used

For this project we used the following components.
- Raspberry Pi 3 Model B (RPi 3/4 are preferable as they have more powerful CPUs)
- Any USB camera supported by Raspberry Pi, camera module caused bugs with the current code version, plus the possibility to modify the code to use it (Google Raspberry Pi Offical Camera with OpenCV).
- Motion sensor
- Disatnce sensor
- Bread board
- HDMI cable
- SD card (32 Go)

## What's in this repository

Currently the following applications are implemented:

- `camera-test`: Test if the camera is working
- `Motion_Detection/motion-detection`: Detect any motion in the frame
- `Object_tracking/object-tracking-color`: Object detection & tracking based on color
- `Object_tracking/object-tracking-shape`: Object detection & tracking based on shape
- `Object_tracking/object-tracking-feature`: Object detection & tracking based on features using ORB
- `Face_detection/face-detection`: Face detection & tracking

## License
© This source code is licensed under the [MIT License](LICENSE).
