# **Face Recognition with OpenCV**

This repository contains a Python-based face recognition program that detects and identifies faces in real time using OpenCV and the `face_recognition` library.

## **Features**
Loads known faces from the `faces/` directory
Captures video from the webcam
Detects and recognizes faces in real-time
Displays identified names on the video feed
Installation

## **Requirement**

Make sure you have the following dependencies installed:

Python 3.x

OpenCV (cv2)

face_recognition library

numpy

You can install the required packages using:

```sh
pip install face_recognition opencv-python numpy
```

## **Usage**

1. Place images of known individuals inside the faces/ directory. 
The filenames should be in the format: name.jpg (e.g., john_doe.jpg).

2. Run the script:
```sh
python face_recognition.py
```

3. The program will start the webcam and attempt to recognize faces.

4. Press the spacebar ( ) to stop the program.

## **How It Works**

1. Loads and encodes images from the faces/ directory.

2. Captures video frames from the webcam.

3. Detects faces and encodes them.

4. Compares detected face encodings with stored face encodings.

5. Displays recognized names and marks faces with bounding boxes.

## **Directory Structure**
```
project_folder/
│-- face_recognition.py
│-- faces/
│   │-- person1.jpg
│   │-- person2.jpg
│-- README.md
```
## **License**
This project is open-source and available under the MIT License.
