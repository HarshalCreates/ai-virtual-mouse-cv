# AI Virtual Mouse using Hand Tracking

An AI-powered virtual mouse that uses hand gestures to control mouse movements and perform actions using computer vision. This project utilizes **OpenCV** and **MediaPipe** for real-time hand detection and gesture recognition, replacing the need for a physical mouse.

---

## ✨ **Features**
- Real-time hand tracking using a webcam
- Control mouse pointer using hand movements
- Perform click using finger gestures
- Scroll up and down with intuitive gestures
- Simple and user-friendly interface

---

## 🛠 **Tech Stack**
- **Python**
- **OpenCV** - For image and video processing
- **MediaPipe** - For hand tracking and gesture detection
- **Numpy** - For mathematical operations
- **PyAutoGUI** - For simulating mouse actions

---

## 💡 **Prerequisites**
Ensure you have Python installed and install the required packages using the following commands:

```bash
pip install opencv-python
pip install mediapipe
pip install numpy
pip install pyautogui
```

---

## 📝 **How to Run**
1. Clone the repository:
    ```bash
    git clone https://github.com/HarshalCreates/ai-virtual-mouse-cv.git
    cd VirtualMouseAi
    ```

2. Run the Python script:
    ```bash
    python VirtualMouseAi.py
    ```

3. Ensure your webcam is connected.
4. Control your mouse using gestures!

---


## 🔎 **How It Works**
- **Hand Detection:** Uses **MediaPipe** to detect hand landmarks in real-time.
- **Finger Tracking:** Identifies finger movements using key landmarks.
- **Mouse Control:** Maps hand positions to screen coordinates using a smooth scaling algorithm.
- **Gesture Recognition:** Detects gestures for left-click, right-click, and scrolling using the distance between fingers.

---



## ✅ **Future Enhancements**
- Add additional gesture-based controls
- Improve gesture recognition accuracy
- Support for multi-hand interactions

---

## 🧑‍💻 **Contributing**
Contributions are welcome! Feel free to submit issues and pull requests.

---



## 📢 **Acknowledgments**
- [OpenCV](https://opencv.org/)
- [MediaPipe](https://developers.google.com/mediapipe/)
- [PyAutoGUI](https://pypi.org/project/PyAutoGUI/)

---

## 👤 **Contact**
For any inquiries, feel free to reach out at [harshalsharma288@gmail.com](mailto:harshalsharma288@gmail.com) or create an issue on GitHub.

