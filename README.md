<h1>👨‍💻 Real-Time Face Detection using OpenCV</h1>

<h2>🌟 Introduction</h2>

This project implements real-time face detection using OpenCV's Haar Cascade Classifier. It captures live video from the webcam, converts frames to grayscale, and detects faces using a pre-trained model. Detected faces are highlighted with a green rectangle.

<h2>📚 Features</h2>

✅ Real-time face detection

✅ Uses OpenCV's Haar Cascade classifier

✅ Converts video frames to grayscale for better accuracy

✅ Highlights detected faces with a bounding box

✅ Stops on pressing 'A'

<h2>📝 Requirements</h2>

Ensure you have the following dependencies installed:

pip install opencv-python

<h2>👷️ Installation</h2>

Clone this repository:

git clone https://github.com/yourusername/face-detection.git
cd face-detection

Install OpenCV if not already installed:

pip install opencv-python

Run the script:

python face_detection.py

<h2>📹 How It Works</h2>

Loads the Haar Cascade face detection model.

Captures live video from the webcam.

Converts frames to grayscale (for better processing).

Detects faces in each frame.

Draws a green rectangle around detected faces.

Press 'A' to exit the program.

<h2>🌟 Output Preview</h2>

When a face is detected, a green rectangle appears around it:

+------------------+
|  😍 🎥 Face Detected  |


![Screenshot 2025-03-28 155138](https://github.com/user-attachments/assets/a1568a95-d545-4662-be17-6112f5b76483)
![Screenshot 2025-03-28 155247](https://github.com/user-attachments/assets/3fe590df-bc1f-43ca-a621-da451c083f11)


+------------------+

<h2>🛠️ Future Improvements</h2>

🔍 Enhance accuracy with Deep Learning models (like DNN or CNNs).

🎨 Add facial landmark detection.

📲 Implement mobile compatibility.
