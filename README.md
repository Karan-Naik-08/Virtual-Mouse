
# Virtual Mouse using Hand Tracking

This project demonstrates how to use hand tracking with MediaPipe and OpenCV to simulate a virtual mouse. The webcam captures hand movements, which are processed to move the mouse cursor. Clicking is triggered when the index finger and thumb are brought close together.

## Features
- Real-time hand tracking using MediaPipe.
- Cursor movement based on index finger position.
- Clicking action triggered by bringing the thumb and index finger close together.

## Installation

To run this project, you need to install the required dependencies. You can install them using `pip`:

```bash
pip install opencv-python mediapipe pyautogui
```

## How to Use

1. **Set Up Webcam**: The webcam will capture the hand movements.
2. **Move Mouse Cursor**: The position of your index finger controls the mouse cursor.
3. **Click Functionality**: Bring your thumb and index finger together to simulate a click.

### Steps:

- Run the script:
  ```bash
  python vm.py
  ```
- A window will open, displaying the webcam feed with hand landmarks tracked.
- Move your hand in front of the camera to control the mouse cursor.
- Bring your thumb and index finger together to click.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI

## File Structure

- `vm.py`: Main script that handles webcam input, hand tracking, and mouse control.
