# Hand-Gesture-Brightness-Control
A Python project to control system brightness using Hand Gestures with MediaPipe and OpenCV.

### How it works:
This application uses a real-time camera feed. By measuring the distance between  **index finger** and **thumb**, the code calculates how much to increase or decrease the brightness. I used **MediaPipe** for hand tracking and **OpenCV** for the visual interface.

### Tech Stack:
* **Python**: The core language used.
* **OpenCV**: For handling the webcam feed.
* **MediaPipe**: For detecting hand landmarks and finger positions.
* **Screen-Brightness-Control**: To communicate with the system's brightness settings.

### How to use:
1. Download the repository.
2. Install the requirements using: `pip install -r requirement.txt`
3. Run the script: `python MainCode.py`

<img width="815" height="625" alt="Screenshot 2026-05-11 101744" src="https://github.com/user-attachments/assets/336825b1-64f4-479f-991b-ab09d349997d" />
<img width="701" height="610" alt="Screenshot 2026-05-11 101833" src="https://github.com/user-attachments/assets/bc90cafd-a0ca-4fc9-93e2-917e4e9193bc" />
<img width="786" height="640" alt="Screenshot 2026-05-11 101917" src="https://github.com/user-attachments/assets/b2a89fd2-ff69-4ce4-879a-681ba0a977de" />
