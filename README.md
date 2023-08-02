# Hand Gesture Control using Python 🖐️👋

This Python program utilizes computer vision and keyboard control to interpret hand gestures and perform corresponding actions. It uses the `cv2` library for image processing, the `cvzone` module for hand tracking, and the `pynput` library for keyboard control.

## Requirements 🛠️

- Python 3.x
- OpenCV (`cv2`)
- cvzone (`HandTrackingModule`)
- pynput

## Usage 🚀

1. Install the required libraries:

   ```bash
   pip install opencv-python pynput
   pip install cvzone
   
## How it works 🤔
The program captures video input from the default camera, tracks hand gestures using the HandDetector from cvzone, and maps these gestures to keyboard commands using the pynput library.

✋ If all fingers are closed, the program simulates pressing the Left Arrow key to move left.
🖐️ If all fingers are open, the program simulates pressing the Right Arrow key to move right.

## Customization 🎨
You can customize the gesture-to-action mapping by modifying the fingers list based on your preference.

## Acknowledgments 🙌
This project was created with the help of the cvzone and pynput libraries.
