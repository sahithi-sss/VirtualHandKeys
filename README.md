# VirtualHandKeys: A Gesture-Based Virtual Keyboard

**🌟 Revolutionizing Typing with Hand Gestures and Computer Vision 🌟**

VirtualHandKeys is a virtual keyboard system designed to translate hand gestures into keyboard inputs, enabling intuitive typing and navigation using computer vision. This innovative project utilizes OpenCV, cvzone, and HandTrackingModule to track hand movements and detect gestures, allowing users to simulate keystrokes with simple hand gestures.


# Table of Contents -

Project Overview

Uses and Significance

How the Project Works

Installation

Directory Structure

Dependencies

Program Execution

Future Enhancements

Contributing

# Project Overview -

This project provides a virtual keyboard that supports typing letters, numbers, symbols, and basic commands through hand gestures. Leveraging computer vision, VirtualHandKeys identifies and interprets hand movements to simulate keystrokes, making it ideal for use cases where touchless control is preferred. The virtual keyboard interface includes various functionalities, from basic typing to more complex actions such as Shift, Caps Lock, symbol toggling, and more.


# Key Features -

*Hand Detection*: Tracks hand gestures in real-time using a webcam.

*Alphabet, Number, and Symbol Input* : Supports typing letters (A-Z), numbers (0-9), and symbols like #, <, |, etc.

*Shift & Caps Lock* : Toggle between uppercase and lowercase letters with Shift and Caps Lock.

*Symbols Toggle* : Switch between alphabet and symbol layouts via a dedicated "Symbols" button.

*Text Navigation* : Standard keys like Space, Enter, and Backspace are available for text input and editing.

*Arrow Keys* : Allows movement within the text using arrow keys (Left, Right, Up, Down).

*Tab Key* : Supports tabbing for indentation.

*Dynamic Feedback* : Displays typed text on-screen in real-time, enhancing user interaction.


# Uses and Significance -

This gesture-based virtual keyboard allows users to type hands-free, making it ideal for accessibility use cases and applications where touchless interaction is desired. With its adaptable layout and precise gesture control, VirtualHandKeys offers a unique, interactive approach to typing and text navigation through simple hand gestures.


# How the Project Works -

**The system processes a live webcam feed to detect hand gestures and track fingertip positions. The following steps describe its functionality:**

*Hand Detection* : Using OpenCV and cvzone, the program tracks hand landmarks to identify gestures and finger positions.

*Gesture Recognition* : The tip of the index finger hovers over virtual keys, and gestures (e.g., bringing two fingers together) simulate a "click," registering a keypress.

*Keyboard Interaction* : Users can interact with the virtual keyboard layout for letters, numbers, symbols, and special keys (e.g., Shift, Enter, Backspace), all displayed dynamically on the screen.


# Installation

To start using VirtualHandKeys, follow these steps:

**Clone the repository:**

git clone https://github.com/sahithi-sss/VirtualHandKeys.git

**Install required dependencies:**

pip install opencv-python cvzone pynput


# Directory Structure -

**The project directory is organized as follows:**

├── VirtualHandKeys

│   ├── main.ipynb            (Notebook for running the VirtualHandKeys program)

│   ├── modules               (Custom modules for hand tracking and keyboard interaction)

│   ├── README.md

└── ├── data                  (Optional data folder for saving configurations)


# Dependencies -

**This project requires Python 3.x and the following libraries:**

*OpenCV* : For video processing and hand tracking.

*cvzone* : Simplifies computer vision functions and hand gesture tracking.

*HandTrackingModule* : A custom module for precise hand landmark detection.

*pynput* : Simulates keyboard inputs based on detected gestures.


**Install all dependencies with:**

pip install opencv-python cvzone pynput


# Program Execution -

**To run VirtualHandKeys:**

Open main.ipynb in Jupyter Notebook or convert it to Python code if running outside of Jupyter.

Run the notebook and follow the on-screen instructions to activate your webcam feed.

Interact with the virtual keyboard using your hand gestures as per the guidance.


**Keyboard Controls:**

Hover the index finger over a key to select it.

Close the middle and index fingers to "click" and register the key.

Navigate between alphabets, symbols, and use special keys (Shift, Enter, Caps Lock, etc.) for seamless typing.


# Future Enhancements -

*Multi-language Support* : Explore support for various languages to expand accessibility.

*Accessibility Enhancements* : Customizable layouts and additional input methods for users with special requirements.


# Contributing -

Contributions are welcome! Fork the project, make enhancements or bug fixes, and submit a pull request.


# License -

This project is licensed under the MIT License
