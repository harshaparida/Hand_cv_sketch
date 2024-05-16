**HandCV Sketch**

**Description:**
HandCV Sketch is a drawing application that harnesses the power of computer vision to enable users to create digital art through hand gestures. Built upon the OpenCV library for computer vision and utilizing the MediaPipe library for hand detection, this application offers a seamless interface where users can draw on a virtual canvas using intuitive hand movements. With HandCV Sketch, users can paint, switch colors, and clear the canvas, all through natural gestures, providing a delightful experience for digital artists.

**Installation:**
1. Clone the repository: `git clone https://github.com/your_username/handcv-sketch.git`
2. Install the required dependencies:
   - OpenCV: `pip install opencv-python`
   - NumPy: `pip install numpy`
   - MediaPipe: `pip install mediapipe`

**Usage:**
1. Run the `handcv_sketch.py` script.
2. A window will open displaying the webcam feed and the canvas.
3. Place your hand within the camera's view to start drawing.
4. Use your index finger to sketch on the canvas.
5. Move your thumb to select different colors (blue, green, red, yellow).
6. To clear the canvas, position your hand over the "CLEAR" button and move your thumb upwards.
7. Press 'q' to exit the application.

**Files Included:**
- `main.py`: Main Python script containing the application code.
- `README.md`: Readme file providing instructions and information about the project.
