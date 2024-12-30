# Real-Time Object Detection Using YOLOv8 and Webcam YOLOv8

This project provides a user-friendly GUI application for performing real-time object detection using a webcam and the YOLOv8 model. It allows users to detect objects in real-time, count the number of objects, and save the annotated video. The application supports multiple YOLOv8 model sizes, making it flexible for different use cases.

# Features
Multiple YOLOv8 Models: Choose from different YOLOv8 model sizes (yolov8n.pt, yolov8s.pt, yolov8m.pt, yolov8l.pt, yolov8x.pt) for varying levels of accuracy and speed.

Real-Time Object Detection: Detect objects in real-time using your webcam.

Object Counting: Count the number of detected objects and display the count on the video feed.

Save Annotated Video: Save the annotated video to your local machine.

FPS Display: Display the frames per second (FPS) on the video feed.

User-Friendly GUI: Built with tkinter, the interface is intuitive and easy to use.

# Use Cases
Real-Time Surveillance: Monitor and detect objects in real-time.

Object Counting: Count the number of specific objects in a video stream (e.g., people, cars, animals).

Video Annotation: Automatically annotate video streams with bounding boxes and labels.

Education and Research: Learn and experiment with YOLOv8 and real-time object detection techniques.

# Getting Started
## Prerequisites
Before running the project, ensure you have the following installed:

Python 3.7 or higher

torch (PyTorch)

ultralytics (YOLOv8)

opencv-python (OpenCV)

Pillow (PIL)

tkinter (usually comes pre-installed with Python)

#Installation
Clone the repository:

git clone https://github.com/alirzx/Real-Time-Object-Detection-Using-YOLOv8-and-Webcam.git
cd Real-Time-Object-Detection-Using-YOLOv8-and-Webcam
Install the required Python packages:

pip install torch ultralytics opencv-python Pillow
Usage
Run the application:


python webcam_object_detection.py
Select a Model:

Use the dropdown menu to choose a YOLOv8 model (default is yolov8n.pt).

Select Save Path:

Click the "Select Save Path" button to choose where to save the annotated video (default is output_video.avi).

Start Webcam:

Click the "Start Webcam" button to begin real-time object detection.

The video feed with bounding boxes, labels, object count, and FPS will be displayed.

Stop Webcam:

Click the "Stop Webcam" button to stop the video feed and object detection.


Start Webcam
Start the webcam for real-time object detection.

Real-Time Detection
Real-time object detection with bounding boxes, labels, object count, and FPS.

Save Video
Save the annotated video to your local machine.

Supported Models
The application supports the following YOLOv8 models:

Model	Description
yolov8n.pt	Nano (fastest, lowest accuracy)
yolov8s.pt	Small
yolov8m.pt	Medium
yolov8l.pt	Large
yolov8x.pt	Extra Large (slowest, highest accuracy)
Contributing
Contributions are welcome! If you’d like to contribute, please follow these steps:

## Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes.

Push your branch and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Ultralytics for the YOLOv8 model.

OpenCV for video processing.

Tkinter for the GUI.

Contact
For questions or feedback, feel free to reach out:

Name: Alira hshmi

Email: alirahshmi@gmail.com

GitHub: alirzx

Enjoy using the Real-Time Object Detection Using YOLOv8 and Webcam application! 🚀😊
