# Smart_Attendance_System_Pro
Smart Attendance System Using face Recognition
The objective of this project is to process live video-stream of students entering their classroom and generate the list of students attending the class. The system is coded in Python 2.7 using OpenCv 3.1.0-dev, Tkinter and Numpy libraries. The file in the directory are:

attendencesystem.py: This is the main script of the project. It implements the GUI of the project and calls functions from the modules package developed.

haarcascade_frontalface_default.xml: This file is taken from the OpenCV library and contains trained configurations of Voila-Jones Algorithm for detecting faces.

Modules: This directory contains files which have helper functions for better structuring of the code.

predict.py: This contains the functions : identify_images(path): To recognise faces from an image. predict_video(path): To recognise faces from a video.
training.py: This contains the functions: train_models(path): To train the prediction models with the training set images. read_images(path): To fetch the face feature matrix from the subdirectories within a directory.