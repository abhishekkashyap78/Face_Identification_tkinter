# Face_Identification_tkinter
📌 Overview

Face Identification using Tkinter is a Python-based desktop application that detects and identifies human faces in real time using a webcam. The project combines OpenCV for computer vision and Tkinter for a simple graphical user interface.

✨ Features

Real-time face detection using Haar Cascade

Face identification using LBPH algorithm

Easy-to-use Tkinter GUI

Works on CPU (no GPU required)

Suitable for beginners and academic projects

🧠 How It Works

The webcam captures live video frames.

Faces are detected using Haar Cascade Classifier.

Detected faces are converted to grayscale.

The trained LBPH model compares faces with stored data.

If a match is found, the user ID/name is displayed; otherwise, Unknown is shown.

🛠️ Technologies Used

Python

OpenCV

Tkinter

NumPy

Pillow

LBPH Face Recognizer

📁 Project Structure
Face_Identification_Tkinter/
│
├── dataset/
│   ├── user.1.1.jpg
│   ├── user.1.2.jpg
│
├── trainer/
│   └── trainer.yml
│
├── haarcascade_frontalface_default.xml
├── train_model.py
├── app.py
├── README.md

⚙️ Installation

Clone the repository or download the project files.

Install the required libraries:

pip install opencv-python opencv-contrib-python pillow numpy

▶️ Usage

Add face images to the dataset folder.

Run the training script:

python train_model.py


Start the application:

python app.py


The Tkinter window will open and start face identification using your webcam.

🎯 Applications

Student projects

Attendance systems

Access control systems

Learning computer vision concepts

🚀 Future Enhancements

Add user registration through GUI

Store user details in a database

Improve accuracy using deep learning models

👨‍💻 Author

Abhishek Kashyap
Aspiring Data Analyst / ML Engineer