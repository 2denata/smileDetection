# Smile Detection using OpenCV

This project uses OpenCV to detect faces and smiles in real-time through a webcam feed. It uses Haar Cascades for face, eye, and smile detection.

# Features
- Real-time face detection.
- Smile detection within detected faces.
- Visualizes detections by drawing rectangles around faces and smiles.

# Requirements
To run this project, you need to have the following installed:
- Python 3.x
- OpenCV (`cv2`)

# How to Run
1. Clone this repository to your local machine.
Ensure you have OpenCV installed using the command:
``` bash
pip install opencv-python
```
2. Run the script:
``` bash
python smileDetection.py
```
The program will open a video stream using your webcam. To stop the video stream, press the q key.

# How It Works
- The program captures video frames from the webcam in real-time.
- Each frame is converted to grayscale and processed using the Haar Cascade Classifiers for face, eye, and smile detection.
- Rectangles are drawn around detected faces and smiles to visualize the detections.
  
# Example
When the program is running, it looks like this:
- Faces are highlighted with a blue rectangle.
- Smiles are highlighted with a red rectangle.

# Acknowledgements
- OpenCV Haar Cascades were used for face and smile detection.
- The code was adapted from the OpenCV tutorials and examples.
