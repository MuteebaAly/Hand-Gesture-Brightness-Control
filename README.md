# Hand-Gesture-Brightness-Control
A Python project to control system brightness using Hand Gestures with MediaPipe and OpenCV.

### How it works:
This application uses a real-time camera feed. By measuring the distance between your **index finger** and **thumb**, the code calculates how much to increase or decrease the brightness. I used **MediaPipe** for hand tracking and **OpenCV** for the visual interface.

### Tech Stack:
* **Python**: The core language used.
* **OpenCV**: For handling the webcam feed.
* **MediaPipe**: For detecting hand landmarks and finger positions.
* **Screen-Brightness-Control**: To communicate with the system's brightness settings.

### How to use:
1. Download the repository.
2. Install the requirements using: `pip install -r requirement.txt`
3. Run the script: `python MainCode.py`
