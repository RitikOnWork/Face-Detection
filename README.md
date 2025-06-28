# 👤 Real-Time Face Detection Using OpenCV

This is a simple and efficient **real-time face detection** project built using **Python** and **OpenCV**. It uses Haar Cascade classifiers to detect human faces from the live webcam stream and outlines them with bounding boxes.

---

## 📚 Technologies Used

- 🐍 Python 3
- 📷 OpenCV (cv2)
- 📁 Haar Cascade Classifier

---

## 🚀 How It Works

1. OpenCV captures video from your default webcam.
2. Each frame is converted to grayscale, which is required by the Haar classifier.
3. The face detection model (`haarcascade_frontalface_default.xml`) detects any faces in the frame.
4. Green rectangles are drawn around all detected faces.
5. The live stream with face detection runs until the **'a'** key is pressed to exit.

---

## 🛠️ Setup & Installation

### 🔧 Requirements

Make sure you have Python installed, then install OpenCV:

<pre><br>pip install opencv-python<br></pre>

---

### ▶️ Run the Program
Make sure your webcam is connected and run:

<pre><br>python face_detection.py<br></pre>
Press "a" to stop the video and close the window.


### 📁 Haar Cascade XML
OpenCV provides pre-trained Haar Cascade models. This project uses:
<pre><br>cv2.data.haarcascades + "haarcascade_frontalface_default.xml"<br></pre>

No additional download is needed as OpenCV installs these with opencv-python.

### ✅ Features
- Real-time face detection using webcam.

- Uses pre-trained Haar Cascade classifier.
  
- Lightweight and easy to run on most systems.

### 📌 Notes
- Lighting conditions may affect accuracy.

- Works best with frontal faces and stable lighting.

### 🤝 Contributing
Feel free to fork the repository and submit a pull request if you improve or enhance the project!
