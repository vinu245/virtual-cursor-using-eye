# virtual-cursor-using-eye

# Introduction

The Virtual Mouse Using Eye Tracking is an innovative system that allows users to control the mouse pointer using eye movements. This project leverages computer vision and machine learning techniques to track eye gaze and translate it into cursor movement and click actions.

# Features

Eye Movement Tracking: Move the cursor based on eye gaze direction.

Blink Detection: Blink to simulate left and right mouse clicks.

Hands-Free Operation: Ideal for users with physical disabilities.

Customizable Sensitivity: Adjust tracking precision based on user preference.

# Requirements

Python 3.x

OpenCV

NumPy

PyAutoGUI

# Installation

Clone the repository:

git clone https://github.com/yourusername/virtual-mouse-eye-tracking.git
cd virtual-mouse-eye-tracking

# Install dependencies:

pip install opencv-python dlib numpy pyautogui imutils

# Run the script:

python virtual_mouse.py

# How It Works

The program captures video using a webcam.

Facial landmarks are detected using dlib’s pre-trained model.

The eye gaze direction is analyzed to determine cursor movement.

Blinks are detected to simulate mouse clicks.

# Usage

Move the Cursor: Look in the desired direction.

Left Click: Blink once.

Right Click: Blink twice.

Exit the Program: Press ESC key.

# Troubleshooting

Ensure proper lighting conditions for accurate eye tracking.

Adjust webcam angle for better face detection.

If performance is slow, reduce webcam resolution.

# Future Enhancements

Implement deep learning for better accuracy.

Add support for multiple monitors.

Integrate voice commands for additional control.

