# AI-Attendance-Management-System
# Face Recognition Attendance System
The Face Recognition Attendance System is a Python-based application that leverages computer vision techniques to recognize faces in real-time using a webcam feed. It automates attendance marking by comparing detected faces against a predefined database of known individuals.

## Key Features
Real-time Face Detection and Recognition:

Utilizes the face_recognition library for face detection and encoding from live video frames.
Compares detected faces against a set of known faces to recognize individuals.
### Attendance Logging:

Automatically logs attendance with timestamps for recognized faces.
Stores attendance records in a CSV file named with the current date for easy integration with other systems.
User Interface (Streamlit):

Provides a user-friendly GUI using Streamlit to display the live video feed and recognized faces.
Enables interactive control and real-time updates of attendance records.
### CSV Export:

Attendance records are saved in a CSV file, facilitating easy integration with attendance management systems.
Requirements
Python 3.x
OpenCV (cv2) library
face_recognition library (Install using pip install face_recognition)
numpy library (for array operations)
datetime module (for timestamping)
Streamlit (for deploying the web application; Install using pip install streamlit)
