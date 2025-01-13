# Face Detection with OpenCV

This project demonstrates real-time face detection using Python and OpenCV. It captures video from a camera, detects faces, and highlights them with rectangles. If no face is detected, it displays a message.

---

## Features
- Real-time face detection
- Face annotation with rectangles
- "No face detected" message
- Quit the application with `Q`

---

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/venkat9310/python_project.git
   cd python_project
   ```

2. **Set Up a Virtual Environment (Optional)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install opencv-python
   ```

4. **Verify Installation**:
   ```bash
   python -c "import cv2; print(cv2.__version__)"
   ```

5. **Run the Script**:
   ```bash
   python face_detection.py
   ```

---

## Troubleshooting
- **Camera Issues**: Ensure the camera is connected and not in use by another application.
- **Classifier Error**: Verify `haarcascade_frontalface_default.xml` exists in OpenCV's data directory.

---

## License
This project is open-source under the MIT License.

---

## Acknowledgments
- OpenCV for computer vision tools.
- Python community for extensive support.

