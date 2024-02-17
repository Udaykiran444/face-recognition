**Face Recognition Flask Application**
This Flask application provides real-time face recognition using the OpenCV and face_recognition libraries. It captures video from the webcam, detects faces, and recognizes known faces in the captured frames.

**Description**
The Face Recognition Flask Application allows users to recognize known faces in real-time video streams. It detects faces in each frame of the video and compares them with known faces to determine if there's a match. If a known face is detected, the application displays the name of the person associated with that face.

**Features**
Real-time face recognition: The application captures video from the webcam and performs face recognition in real-time.
Known face detection: Recognizes known faces and displays their names in the video stream.
User-friendly interface: Provides a simple web interface to view the video stream and recognized faces.
Dependencies
**This project relies on the following libraries:**

Flask: For building the web application framework.
OpenCV: For capturing video frames from the webcam and image processing.
face_recognition: For face detection and recognition.
NumPy: For numerical operations.
Getting Started

**To run the application, follow these steps:**

Ensure you have Python installed on your system.
Install the required dependencies using pip:
Copy code
pip install flask opencv-python-headless face_recognition numpy
Clone or download the repository to your local machine.
Navigate to the project directory and run the app.py file using Python:
Copy code
python app.py
Open a web browser and navigate to http://localhost:5000 to access the application.
**Usage**
On the homepage, the application displays the video stream captured from the webcam.
Known faces detected in the video stream are highlighted with a bounding box, and their names are displayed below the faces.
**Customization**
You can customize the known faces by adding more images of known individuals to the known_face_encodings list in the app.py file. Ensure that each known face image is properly encoded using the face_recognition library.

**Contributions**
Contributions to this project are welcome. Feel free to submit issues or pull requests.
