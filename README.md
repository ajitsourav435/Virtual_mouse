# Hand Gesture Mouse Control

This project uses computer vision and machine learning techniques to control the mouse and perform actions using hand gestures. The system uses OpenCV and MediaPipe to detect hand landmarks and PyAutoGUI to control the mouse and take screenshots.

## Features

- **Move Mouse**: Move the mouse cursor using the tip of your index finger.
- **Left Click**: Perform a left-click gesture.
- **Right Click**: Perform a right-click gesture.
- **Double Click**: Perform a double-click gesture.
- **Screenshot**: Take a screenshot using a specific hand gesture.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI
- Pynput
- Util (custom utility functions)

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/hand-gesture-mouse-control.git
    cd hand-gesture-mouse-control
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv venv
    ```

3. **Activate the Virtual Environment**:

    - **Windows**:
        ```bash
        venv\Scripts\activate
        ```
    - **macOS/Linux**:
        ```bash
        source venv/bin/activate
        ```

4. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Script**:
    ```bash
    python project2.py
    ```

2. **Control the Mouse**:
    - **Move Mouse**: Move your index finger to move the mouse cursor.
    - **Left Click**: Perform the left-click gesture.
    - **Right Click**: Perform the right-click gesture.
    - **Double Click**: Perform the double-click gesture.
    - **Screenshot**: Perform the screenshot gesture to take a screenshot.

3. **Exit**: Press `q` to exit the application.

## Hand Gestures

- **Move Mouse**: Move your index finger.
- **Left Click**: Form a left-click gesture.
- **Right Click**: Form a right-click gesture.
- **Double Click**: Form a double-click gesture.
- **Screenshot**: Form a screenshot gesture.

## Custom Utility Functions

Ensure you have a `util.py` file with necessary utility functions like `get_angle()` and `get_distance()` for calculating angles and distances between hand landmarks.

## Contributing

Feel free to open issues or submit pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [MediaPipe](https://mediapipe.dev/) for hand tracking.
- [OpenCV](https://opencv.org/) for computer vision functions.
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) for mouse control and screenshots.
- [Pynput](https://pypi.org/project/pynput/) for advanced mouse control.
