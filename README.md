**# Real Time Human Action REcognition using mediapipe & TensorFlow**
This project implements a real-time human gestue/acrtion recognition system using mediapipe for landmark detection and tensorflow for sequence modeling with LSTM layers.

**# 🚀 Features**
📍 pose, face, and hand landmark detection using google mediapipe
📍 Real-time webcam input and processing with openCV
📍 Data Collection, preprocessing, and visualisation utilities
📍 Visual feedback with overlaid landmark drawing and predicted actions.

**# 🛠️ TEch Stack**

📍 Python 3.x
📍 TensorFlow 2.17.0
📍 Mediapipe
📍 OpenCV
📍 Scikit-learn
📍 Matplotlib

**# 📦 Installation**

 pip install --upgrade pip
 pip install tensorflow==2.17.0 opencv-python mediapipe scikit-learn matplotlib

**🧠 Model Overview**
 The model uses mediapipe to extract face,pose,and hand keypoints and feeds sequences of these into an LSTM network to classify different gestures or actions.

**📂 Project Structure**

 ├── data/                # Collected keypoint sequences
 ├── Final.ipynb          # Main Jupyter Notebook
 ├── model/               # Trained model (optional)
 ├── utils/               # Utility functions
 ├── README.md
 
**🧪 How to Run**
 1> Open the Final.ipynb notebook.
 2> Run all cells to:
    -> Collect data
    -> Train the model
    -> Run real-time recognition using webcam
make sure your webcam is enabled and permissions granted.

**🎯 Use Cases**
--> Sign language detection
--> Gesture-based control systems
--> Interactive educational tools

**📌 To DO**
--> Improve model accuracy with more training data
--> Add GUI interface
--> Deploy as a web app or mobile solution
