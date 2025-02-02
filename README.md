# Hand Gesture Mouse Control

This project allows you to control your computer mouse using hand gestures via a webcam. It utilizes **OpenCV, MediaPipe (via HandTrackingModule), and PyAutoGUI** to detect hand movements and perform mouse actions like moving, clicking, right-clicking, and even taking screenshots.

## 🚀 Features

- **Hand Tracking**: Uses a custom HandTrackingModule to detect hands.
- **Mouse Movement**: Move the cursor by moving your index finger.
- **Clicking Actions**:
  - Index finger up → Move cursor
  - ![Alt text](images/Cursor.gif)
  - Index & middle fingers up and bring them close together → Left click
  - - ![Alt text](images/Left_Click.gif)
  - Three fingers up → Right click
  - - ![Alt text](images/Right_Click.gif)
- **Screenshot Capture**: Raise all five fingers to trigger a screenshot.
- - ![Alt text](images/Screenshot.gif)
- **Optimized for Performance**:
  - Uses smoothing for smoother mouse movement.
  - Introduces click delay to avoid unintended multiple clicks.

## 📦 Installation

### 1️⃣ Install Dependencies

Make sure you have Python 3 installed. Then, install the required packages:

```bash
pip install opencv-python numpy pyautogui mediapipe
```

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/hassanalisyed021/Hand-Gesture-Mouse-Control.git
cd hand-gesture-mouse
```

### 3️⃣ Run the Script

```bash
python hand_mouse_control.py
```

## 🖥️ Usage

1. Run the script.
2. Ensure your webcam is working.
3. Move your hand within the webcam frame to control the mouse.
4. Use different gestures to trigger actions (listed above).
5. Press `Q` to exit.

## 🔧 Troubleshooting

- If the cursor movement is **laggy**, ensure no unnecessary background processes are running.
- If gestures are **not detected properly**, adjust your hand position or lighting.
- If the camera **does not open**, ensure that your webcam is working and accessible.

## 📌 Future Improvements

- Add gestures for **scrolling** and **dragging**.
- Improve multi-hand support for **dual-hand actions**.
- Integrate **voice commands** for additional control.

## 🤝 Contributing

Feel free to fork this repo and submit pull requests for improvements.

## ✨ Credits

- **OpenCV** for image processing.
- **MediaPipe** for hand tracking.
- **PyAutoGUI** for mouse automation.

